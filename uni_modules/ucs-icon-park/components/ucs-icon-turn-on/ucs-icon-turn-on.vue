<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《打开》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M21 43C16.2742 41.2327 12.3325 35.1851 10.3597 31.6428C9.50794 30.1134 9.95664 28.2347 11.3236 27.1411C12.8473 25.9222 15.0438 26.0438 16.4236 27.4236L18 29V17.5C18 16.1193 19.1193 15 20.5 15C21.8807 15 23 16.1193 23 17.5V23.5C23 22.1193 24.1193 21 25.5 21C26.8807 21 28 22.1193 28 23.5V25.5C28 24.1193 29.1193 23 30.5 23C31.8807 23 33 24.1193 33 25.5V27.5C33 26.1193 34.1193 25 35.5 25C36.8807 25 38 26.1193 38 27.5V35.368C38 36.4383 37.7354 37.496 37.1185 38.3707C36.0949 39.8219 34.255 42.0336 32 43C28.5 44.5 25.3701 44.6343 21 43Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M12 9L15 12" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M19 4L20 10" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M27 8L25 11" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>