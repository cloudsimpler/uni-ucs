<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《辐射》图标
	 * @tutorial https://ucs.cloudsimpler.com/library/ucs-iconPark
	 * @property {Number} size 图标大小
	 * @property {Number} strokeWidth 线段粗细
	 * @property {String} theme 图标大小
	 * @property {Array} fill 图标颜色，["外部描边颜色","外部填充颜色","内部描边颜色","内部填充颜色"]
	 * @property {String} strokeLinecap 图标大小
	 * @property {String} strokeLinejoin 图标大小
	 */
	export default {
		mixins: [iconMixin],
		computed: {
			iconSvg(): string {
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M24.0039 27C25.6608 27 27.0039 25.6569 27.0039 24C27.0039 22.3431 25.6608 21 24.0039 21C22.3471 21 21.0039 22.3431 21.0039 24C21.0039 25.6569 22.3471 27 24.0039 27Z" fill="${this.colors(0)}"/><path d="M19.0405 31.476C20.4626 32.4194 22.1673 32.9688 24 32.9688C25.8327 32.9688 27.5374 32.4194 28.9595 31.476L35.021 40.6827C31.861 42.7792 28.0727 44 24 44C19.9273 44 16.139 42.7792 12.979 40.6827L19.0405 31.476ZM15.0159 24.484L4.03531 25.145C4.01188 24.7474 4 24.3467 4 23.9432C4 16.0911 8.49944 9.29287 15.0538 6L19.9742 15.8688C17.0247 17.3506 15 20.4098 15 23.9432C15 24.1248 15.0053 24.3051 15.0159 24.484ZM28.0258 15.8688L32.9462 6C39.5006 9.29287 44 16.0911 44 23.9432C44 24.3467 43.9881 24.7474 43.9647 25.145L32.9841 24.484C32.9947 24.3051 33 24.1248 33 23.9432C33 20.4098 30.9753 17.3506 28.0258 15.8688Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>