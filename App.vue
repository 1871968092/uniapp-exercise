<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		},
		onError:function(err){
			console.log('出错拉',err)
		}
	}
</script>

<style>
	/*每个页面公共css */
	@import url("./static/font/iconfont.css");
</style>
