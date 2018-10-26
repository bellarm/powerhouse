<template>
  <div class="home-contact">
    <div class="title">
      SAY HI TO US
    </div><!-- Material form contact -->
    <row>
      <column md="3"></column>
      <column md="6">
      <form style="margin: 20px 20px 20px 20px;">
        <label for="defaultFormContactNameEx" class="grey-text">Name</label>
        <input type="text" id="defaultFormContactNameEx" class="form-control"/>
        <br/>
        <label for="defaultFormContactEmailEx" class="grey-text">Email</label>
        <input type="email" id="defaultFormContactEmailEx" class="form-control"/>
        <br/>
        <label for="defaultFormContactSubjectEx" class="grey-text">Subject</label>
        <input type="text" id="defaultFormContactSubjectEx" class="form-control"/>
        <br/>
        <label for="defaultFormContactMessageEx" class="grey-text">Message</label>
        <textarea type="text" id="defaultFormContactMessageEx" class="form-control" rows="3"></textarea>
        <div class="text-center mt-3">
          <Btn color="cyan" class="btn" type="submit">
            Send<i class="fa fa-paper-plane-o ml-2"></i>
          </Btn>
        </div>
      </form>
    </column>
  </row>
  </div>
</template>

<script>
import { Container, Row, Column, mdbInput, MdTextarea, Btn, Fa, Card, CardBody, Modal, ModalHeader, ModalBody, ModalFooter } from 'mdbvue';

export default {
  name: 'Contact',
  components: {
    Container,
    Row,
    Column,
    mdbInput,
    MdTextarea,
    Btn,
    Fa,
    Card,
    CardBody,
    Modal,
    ModalHeader,
    ModalBody,
    ModalFooter
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-contact {
  padding-top: 30px;
  width: 100%;
  overflow: hidden;
}

.title {
  text-align: center;
  font-size: 50px;
  font-family: 'Lato', sans-serif;
  font-weight: 800;
  color: #black;
}

.subtitle {
  font-size: 20px;
  font-family: 'Lato', serif;
  color: #black;
}

.contact-form {
  font-size: 16px;
  width: 500px;
  padding: 15px 15px;
  border-radius: 4px;
  margin: auto;
  width: 500px;
}

.contact-form .label {
  display: block;
}

</style>
