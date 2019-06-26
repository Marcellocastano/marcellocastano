<template>
	<div class="header">
	  	<div class="top-nav-container">
	  		<a href="">Home</a>
	  		<a href="">About</a>
	  		<a href="">Portfolio</a>
	  	</div>
	  	<div class="logo-box">
			<img src="../assets/image/marc-logo1.png" style="width: 150px;">
		</div>
	  	<div class="top-nav-container">
	  		<a href="">Home</a>
	  		<a href="">Blog</a>
	  		<a href="">Contact</a>
	  	</div>
	</div>
</template>

<style type="text/css">
.header {
    width: 100%;
    display: flex;
    background: linear-gradient(to right, #4288d7 0, #0758b4 51%, #001123 100%);
    box-shadow: 0px 5px 9px 4px rgba(143, 143, 143, 1);
    height: 65px;
    position: relative;
    justify-content: space-evenly;
    align-items: center;
    margin-bottom: 100px;
}
.top-nav-container a {
    padding: 5px 20px;
    width: 150px;
    text-decoration: none;
    color: #efefef;
    font-size: 18px;
}
.logo-box {
	background: linear-gradient(to right, #f7f8fb 0, #c6c5c5 93%);
	border-radius: 85px;
	box-shadow: 0px 5px 9px 0px rgba(143, 143, 143, 1);
    position: absolute;
    top: 0px;
    border: 2px solid #001123;
}
</style>