<template>
  <div class="home-stories">
    <div class="title">
      STORIES
    </div>
      <container>
        <carousel :interval="8000" showControls showIndicators multi slide>
          <carousel-item>
            <row>
              <column md="4">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(34).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>The 5 is Alive</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Read more</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(18).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(35).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
            </row>
          </carousel-item>
          <carousel-item>
            <row>
              <column md="4">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(60).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(47).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(48).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
            </row>
          </carousel-item>
          <carousel-item>
            <row>
              <column md="4">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(53).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(45).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
              <column md="4" class="clearfix d-none d-md-block">
                <card class="mb-2">
                  <card-img src="https://mdbootstrap.com/img/Photos/Horizontal/Nature/4-col/img%20(51).jpg" alt="Card image cap" waves></card-img>
                  <card-body>
                    <card-title>Card title</card-title>
                    <card-text>Some quick example text to build on the card title and make up the bulk of the card's content.</card-text>
                    <btn color="primary">Button</btn>
                  </card-body>
                </card>
              </column>
            </row>
          </carousel-item>
        </carousel>
      </container>
  </div>
</template>

<script>
import { Carousel, CarouselItem, CarouselCaption, Container, Row, Column, Card, CardImg, CardBody, CardTitle, CardText, Btn } from 'mdbvue';

export default {
  name: 'Stories',
  components: {
    Carousel,
    CarouselItem,
    CarouselCaption,
    Container,
    Row,
    Column,
    Card,
    CardImg,
    CardBody,
    CardTitle,
    CardText,
    Btn
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-stories {
  padding-top: 30px;
  width: 100%;
  height: 90vh;
  background-image: url(../assets/image1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  overflow: hidden;
  background-attachment: fixed;
  text-align: center;
}

.title {
  font-size: 50px;
  font-family: 'Lato', sans-serif;
  font-weight: 800;
  color: #fff;
}

.subtitle {
  font-size: 20px;
  font-family: 'Lato', serif;
  color: #fff;
}

</style>
