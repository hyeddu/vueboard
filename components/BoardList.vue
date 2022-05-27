<template>
  <div role="tablist">
    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-1 variant="info">일기쓰기</b-button>
      </b-card-header>
      <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>I start opened because <code>visible</code> is <code>true</code></b-card-text>
          <b-card-text>
            <img src='../static/pic1.jpg' alt='pic1'/> 
          <!-- <b-img :src="require('../static/pic1.jpg')" alt='pic1'></b-img> -->
          {{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-2 variant="info">감사하기</b-button>
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>
           <img src='../static/pic2.jpg' alt='pic2'/>
          {{ text2 }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-3 variant="info">돌아보기</b-button>
      </b-card-header>
      <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>
          <img src='../static/pic3.jpg' alt='pic3'/>
          {{ text3 }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    
  </div>
</template>

<script>
  export default {
    data() {
      return {
        text: `
          오래오래 기억할수 있으니까.
        `,
        text2: `
          긍정적인 사람이 되어있더라. 
        `,
        text3: `
        열심히 살았는지 알수있어 뿌듯해.
        `
      }
    }
  }
</script>