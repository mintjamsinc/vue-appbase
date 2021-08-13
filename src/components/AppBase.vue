<!-- Copyright (c) 2021 MintJams Inc. Licensed under MIT License. -->

<template>
	<div style="position: absolute; top: 0; bottom: 0; left: 0; right: 0;">
		<div style="position: absolute; top: 0; left: 0; right: 0; height: 3rem;">
			<slot name="menubar"></slot>
		</div>
		<div style="position: absolute; top: 3rem; bottom: 0; left: 0; right: 0;">
			<slot></slot>
		</div>
	</div>
</template>
