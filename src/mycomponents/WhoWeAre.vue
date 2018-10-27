<template>
  <div class="home-about">
    <div class="title">
      WHO WE ARE
    </div>
    <p class="dark-grey-text mx-auto mb-5 w-75 text-center">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit id laborum.</p>
      <container>
        <row>
        <column md="4" sm="6">
          <card>
              <view-wrapper hover cascade>
                <card-img src="https://via.placeholder.com/600x400" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
              </card-body>
            </card>
        </column>
        <column md="4" sm="6">
          <card>
              <view-wrapper hover cascade>
                <card-img src="https://via.placeholder.com/600x400" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
              </card-body>
            </card>
          </column>
          <column md="4" sm="6">
            <card>
              <view-wrapper hover cascade>
                <card-img src="https://mdbootstrap.com/img/Photos/Others/men.jpg" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
                <a class="icons-sm fb-ic">
                  <i class="fa fa-facebook"> </i>
                </a>
              </card-body>
            </card>
          </column>
          <column md="4" sm="6">
            <card>
              <view-wrapper hover cascade>
                <card-img src="https://via.placeholder.com/600x400" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
              </card-body>
            </card>
          </column>
          <column md="4" sm="6">
            <card>
              <view-wrapper hover cascade>
                <card-img src="https://mdbootstrap.com/img/Photos/Others/men.jpg" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
              </card-body>
            </card>
          </column>
          <column md="4" sm="6">
            <card>
              <view-wrapper hover cascade>
                <card-img src="https://mdbootstrap.com/img/Photos/Others/men.jpg" alt="Card image cap"></card-img>
                <md-mask flex-center waves overlay="white-slight"></md-mask>
              </view-wrapper>
              <card-body class="text-center" cascade>
                <card-title><strong>Billy Cullen</strong></card-title>
                <h5>Web developer</h5>
                <card-text>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus, ex, recusandae. Facere modi sunt, quod quibusdam.</card-text>
                <a class="icons-sm ins-ic">
                  <i class="fa fa-instagram"> </i>
                </a>
              </card-body>
            </card>
          </column>
        </row>
      </container>

    </div>
</template>

<script>
import { Container, Row, Column, Card, CardImg, CardHeader, CardBody, CardTitle, CardText, CardFooter, CardUp, CardAvatar, CardGroup, CardDeck, Btn, ViewWrapper, MdMask, Fa } from 'mdbvue';

export default {
  name: 'WhoWeAre',
  components: {
    Container,
    Row,
    Column,
    Card,
    CardImg,
    CardHeader,
    CardBody,
    CardTitle,
    CardText,
    CardFooter,
    CardUp,
    CardAvatar,
    CardGroup,
    CardDeck,
    Btn,
    ViewWrapper,
    MdMask,
    Fa
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-about {
  padding-top: 30px;
  padding-bottom: 30px;
  width: 100%;
  overflow: hidden;
  text-align: center;
}


.title {
  font-size: 50px;
  font-family: 'Lato', sans-serif;
  font-weight: 800;
  color: #black;
}

  .card {
    margin-bottom: 30px;
  }

</style>
