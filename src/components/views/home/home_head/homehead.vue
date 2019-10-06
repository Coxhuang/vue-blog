<template>
	<div class="home-head">
		<!-- 导航栏 -->
		<div class="home-head-box">
			<!-- 导航栏-盒子 -->
			<div class="home-head-content">
			<!-- 导航栏-内容 -->
				<ul class="home-head-content-left">
					<!-- 导航栏-内容-左边 -->
					<li>
						<a>
						文章
						</a>
					</li>
					<li>
						<a>
						分享
						</a>
					</li>
					<li>
						<a>
						文档
						</a>
					</li>
					<li>
						<a>
						例子
						</a>
					</li>
				</ul>
				<ul class="home-head-content-right">
					<!-- 导航栏-内容-右边 -->
					<li>
						<!-- <el-form ref="form" :model="form" label-width="80px">
							<el-form-item label="活动名称">
								<el-input v-model="form.name"></el-input>
							</el-form-item>
						</el-form> -->
						<el-input v-model="input" placeholder="搜索" style="background-color:#9caebf" ></el-input>
					</li>
					<li>
						<a>
						登录
						</a>
					</li>
					<li>
						<a>
						注册
						</a>
					</li>
				</ul>
		</div>
		</div>
	</div>
</template>

<script>
	export default {
	name: 'HomeHead',
		data () {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		}
	}
</script>

<style lang="scss" scoped>
	.home-head{
		width: 100%;
		min-height: 60px;
		margin: 0;
		padding: 0;
    	background-color: #9caebf;
		.home-head-box{
			width: 80%;
			min-height: 60px;
			padding: 0 15px;
			margin: 0 auto;
			.home-head-content{
				width: 100%;
				min-height: 60px;
			}
		};
		ul{
			display: inline-block;
			margin: 0;
			padding: 0;
		}
		.home-head-content-left{
			li{
				display: inline-block;
				margin: 0;
				padding: 0;
			}
			a{
				display: inline-block;
				text-align: left;
				width: 62px;
				height: 60px;
				padding: 18px 15px;
				margin: 0;
				color: #fff;
			}
		};
		.home-head-content-right{
			float: right;
			li{
				display: inline-block;
				margin: 0;
				padding: 0;
				.el-input__inner{
					background-color:#9caebf!important;
				}
			}
			a{
				display: inline-block;
				text-align: left;
				width: 62px;
				height: 60px;
				padding: 18px 15px;
				margin: 0;
				color: #fff;
			}
		}
	}
</style>
