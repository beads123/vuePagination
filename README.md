# vuePagination

## 使用方法

<code>

	<template>
		<!-- 分页 -->
		<pagenav v-ref:pagevue></pagenav>
	</template>

	<script>
		import pagenav from 'path/Pagenav'

		export default  {
			data () {
				return {

				}
			},
			components: { 'pagenav': pagenav },
			method:{

			},

			created:{
				// 获取总条数total，计算页数page=total/limit
			  	this.$refs.pagevue.initpage(total,page);
			}
		}
	</script>
</code>

## 依赖的库或者组件

<ul>
	<li>1、vuejs</li>
	<li>2、bootstrap</li>
</ul>

