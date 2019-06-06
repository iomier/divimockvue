<template>
  <div id="cards">
    <Card title="Speak With an Agent" text="Donec rutrum congue leo eget malesuada. Curabitur non nulla sit amet nisl tempus convallis" image="https://www.elegantthemes.com/layouts/wp-content/uploads/2018/07/insurance-14.png" />
    <Card title="File a Claim" text="Donec rutrum congue leo eget malesuada. Curabitur non nulla sit amet nisl tempus convallis" image="https://www.elegantthemes.com/layouts/wp-content/uploads/2018/07/insurance-12.png" />
    <CardLogin title="Manage Your Policies" text="Donec rutrum congue leo eget malesuada. Curabitur non nulla sit amet nisl tempus convallis" image="https://www.elegantthemes.com/layouts/wp-content/uploads/2018/07/insurance-12.png" />
  </div>
</template>
<script>
import Card from "../components/Utils/Card";
import CardLogin from '../components/Utils/CardLogin'
export default {
  name: "Cards",
  components: {
    Card,
    CardLogin
  }
};
</script>
<style lang="sass" scoped>
#cards
  display: flex
  align-content: stretch
  margin: 0 auto
  top: -100px
  width: 80%
</style>