<template>
    <div>
        <b-container fluid class="p-4 bg-dark">
            <b-row>
                <b-col>  
	                <b-img thumbnail fluid :src="require('../static/Ipic1.jpg')" alt="Image 1"></b-img> 
                </b-col>
                <b-col>
		            <b-img thumbnail fluid :src="require('../static/Ipic2.jpg')" alt="Image 2"></b-img> 
                </b-col>
                <b-col>
                    <b-img thumbnail fluid :src="require('../static/Ipic3.jpg')" alt="Image 3"></b-img>
                </b-col>
                <b-col>
                    <b-img thumbnail fluid :src="require('../static/Ipic4.jpg')" alt="Image 4"></b-img>
                </b-col>
                <b-col>
                    <b-img thumbnail fluid :src="require('../static/Ipic5.jpg')" alt="Image 5"></b-img>
                </b-col>
                <b-col>
                    <b-img thumbnail fluid :src="require('../static/Ipic6.jpg')" alt="Image 6"></b-img>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .col:nth-child(3){clear: both;}
</style>