<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《微单》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M44 26C44 28.6393 43.2696 31.1081 42 33.2152C40.8198 35.1737 39.1737 36.8198 37.2152 38C35.1081 39.2696 32.6393 40 30 40C27.3607 40 24.8919 39.2696 22.7848 38C18.7192 35.5502 16 31.0927 16 26C16 20.9073 18.7192 16.4498 22.7848 14C24.8919 12.7304 27.3607 12 30 12C32.6393 12 35.1081 12.7304 37.2152 14C39.1737 15.1802 40.8198 16.8263 42 18.7848C43.2696 20.8919 44 23.3607 44 26Z" fill="${this.colors(1)}"/><path d="M4 14V38H22.7848C18.7192 35.5502 16 31.0927 16 26C16 20.9073 18.7192 16.4498 22.7848 14H4Z" fill="${this.colors(1)}"/><path d="M37.2152 14C35.1081 12.7304 32.6393 12 30 12C27.3607 12 24.8919 12.7304 22.7848 14M37.2152 14H42V18.7848M37.2152 14C39.1737 15.1802 40.8198 16.8263 42 18.7848M22.7848 14H4V38H22.7848M22.7848 14C18.7192 16.4498 16 20.9073 16 26C16 31.0927 18.7192 35.5502 22.7848 38M37.2152 38C35.1081 39.2696 32.6393 40 30 40C27.3607 40 24.8919 39.2696 22.7848 38M37.2152 38H42V33.2152M37.2152 38C39.1737 36.8198 40.8198 35.1737 42 33.2152M42 18.7848C43.2696 20.8919 44 23.3607 44 26C44 28.6393 43.2696 31.1081 42 33.2152" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><rect x="8" y="9" width="9" height="5" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M10 22V30" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M36 26C36 29.3137 33.3137 32 30 32M24 26C24 22.6863 26.6863 20 30 20" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>