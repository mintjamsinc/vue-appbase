<!-- Copyright (c) 2021 MintJams Inc. Licensed under MIT License. -->

<template>
	<div style="position: absolute; top: 0; bottom: 0; left: 0; right: 0;">
		<div style="position: absolute; top: 0; left: 0; right: 0;" :style="{'height': menuHeight}">
			<slot name="menubar"></slot>
		</div>
		<div style="position: absolute; bottom: 0; left: 0; right: 0;" :style="{'top': menuHeight}">
			<slot></slot>
		</div>
	</div>
</template>

<script>
export default {
	props: {
		'menuHeight': {
			'type': String,
			'default': '3rem',
		},
	},
}
</script>
