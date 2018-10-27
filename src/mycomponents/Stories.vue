<template>
  <div class="home-stories">
      <container>

    <div class="title">STORIES</div>
    <p class="white-text mx-auto mb-5 w-75 text-center">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit id laborum.</p>
    <row style="padding-top:20px; background-color: rgba(255, 255, 255, 1);">
      <column md="12" lg="6">
        <div class="mb-4">
          <view-wrapper hover rounded class="z-depth-1-half mb-4">
            <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Slides/1.jpg" alt="Sample image" />
            <a>
              <md-mask overlay="white-slight" class="waves-light" />
            </a>
          </view-wrapper>
          <div class="d-flex justify-content-between">
            <p class="font-weight-bold dark-grey-text">
              <Fa icon="clock-o" class="pr-2" />27/02/2018</p>
            <p class="font-weight-bold dark-grey-text">
              <Fa icon="user-circle-o" class="pr-2" />Author</p>
          </div>
          <h3 class="font-weight-bold dark-grey-text mb-3 p-0">
            <a>Title of the news</a>
          </h3>
          <p class="dark-grey-text mb-lg-0 mb-md-5 mb-4">Sed ut perspiciatis unde voluptatem omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam
            rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae explicabo. Duis aute irure
            dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.</p>
        </div>
      </column>

      <column md="12" lg="6">
        <div class="news">
          <row>
            <column md="3">
              <view-wrapper hover rounded class="z-depth-1-half mb-4">
                <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(29).jpg" alt="Sample image" />
                <a>
                  <md-mask overlay="white-slight" class="waves-light" />
                </a>
              </view-wrapper>
            </column>
            <column md="9">
              <p class="font-weight-bold dark-grey-text">26/02/2018 - Author</p>
              <div class="d-flex justify-content-between">
                <column col="11" class="text-truncate pl-0 mb-3">
                  <a class="dark-grey-text">At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis</a>
                </column>
                <a>
                  <fa icon="angle-double-right" />
                </a>
              </div>
            </column>
          </row>
        </div>

        <div class="news">
          <row>
            <column md="3">
              <view-wrapper hover rounded class="z-depth-1-half mb-4">
                <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Horizontal/Food/4-col/img%20(45).jpg" alt="Sample image" />
                <a>
                  <md-mask overlay="white-slight" class="waves-light" />
                </a>
              </view-wrapper>
            </column>
            <column md="9">
              <p class="font-weight-bold dark-grey-text">25/02/2018</p>
              <div class="d-flex justify-content-between">
                <column col="11" class="text-truncate pl-0 mb-3">
                  <a class="dark-grey-text">Itaque earum rerum hic tenetur a sapiente delectus</a>
                </column>
                <a>
                  <fa icon="angle-double-right" />
                </a>
              </div>
            </column>
          </row>
        </div>

        <div class="news">
          <row>
            <column md="3">
              <view-wrapper hover rounded class="z-depth-1-half mb-4">
                <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/images/87.jpg" alt="Sample image" />
                <a>
                  <md-mask overlay="white-slight" class="waves-light" />
                </a>
              </view-wrapper>
            </column>
            <column md="9">
              <p class="font-weight-bold dark-grey-text">24/03/2018</p>
              <div class="d-flex justify-content-between">
                <column col="11" class="text-truncate pl-0 mb-3">
                  <a class="dark-grey-text">Soluta nobis est eligendi optio cumque nihil impedit quo minus</a>
                </column>
                <a>
                  <fa icon="angle-double-right" />
                </a>
              </div>
            </column>
          </row>
        </div>

        <div class="mb-4">
          <row>
            <column md="3">
              <view-wrapper hover rounded class="z-depth-1-half mb-4">
                <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(27).jpg" alt="Sample image" />
                <a>
                  <md-mask overlay="white-slight" class="waves-light" />
                </a>
              </view-wrapper>
            </column>
            <column md="9">
              <p class="font-weight-bold dark-grey-text">23/02/2018</p>
              <div class="d-flex justify-content-between">
                <column col="11" class="text-truncate pl-0 mb-3">
                  <a class="dark-grey-text">Duis aute irure dolor in reprehenderit in voluptate</a>
                </column>
                <a>
                  <fa icon="angle-double-right" />
                </a>
              </div>
            </column>

          </row>
        </div>

      </column>
    </row>

  </container>
  </div>
</template>

<script>
import { Container, Row, Column, ViewWrapper, Fa, MdMask, Badge } from 'mdbvue';

export default {
  name: 'Stories',
  components: {
    Container,
    Row,
    Column,
    ViewWrapper,
    Fa,
    MdMask,
    Badge
  },

};
</script>

<style scoped>
  .home-stories {
    padding: 30px;
    width: 100%;
    background-image: url(../assets/image1.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;
    background-attachment: fixed;
  }

  .title {
    font-size: 50px;
    font-family: 'Lato', sans-serif;
    font-weight: 800;
    color: #fff;
    text-align: center;
  }
  .news {
    border-bottom: 1px solid #e0e0e0;
    margin-bottom: 1.5rem;
  }
</style>
