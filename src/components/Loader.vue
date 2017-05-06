<template>
    <!-- loader -->
    <div class="loader">
        <h1 class="loadingtext">
        Admin
        <span>9</span>
        </h1><p>Awesome things getting ready...</p>
        <br />
        <img src="./../assets/images/loader2.gif" alt="">
    </div>
    <!-- loader ends -->  
</template>

<script>

</script>

<style scoped>

/*==============================*/
/*====== loader CSS ======*/
/*==============================*/
.loader {
	background: rgba(242, 243, 244, 0.9);
	text-align: center;
	position: fixed;
	height: 100%;
	width: 100%;
	left: 0;
	top: 0;
	z-index: 99999
}
.loadingtext {
	margin-top: 18%;
	font-size: 120px;
	font-weight: 200;
	color: #566b75;
	line-height: 120px;
	position: relative;
}
.loadingtext span {
	font-weight: 400;
	color: #03a9f4;
	font-size: 200px;
	display: inline-block;
	top: 0;
	line-height: 200px;
}
.loader p {
	font-weight: 300;
	color: #666666;
	font-size: 30px;
	display: inline-block;
	top: 0;
	line-height: 50px;
	margin-bottom: 30px;
	text-transform: uppercase
}

</style>