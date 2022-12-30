<script>
	export default {
		// 启动应用触发
		onLaunch: function() {
			//启动界面设为4秒
			setTimeout(() => {
			    plus.navigator.closeSplashscreen();
			}, 3000);
			// 禁止屏幕旋转，保持竖屏
			plus.screen.lockOrientation("portrait-primary");
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
</style>
