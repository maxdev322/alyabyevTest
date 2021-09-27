<template>
  <li class="list__item">
    <strong>{{ id }}. </strong>
    <div>
      <span>Full name:</span> {{ first_name }} {{ last_name }} <br />
      <span>E-mail:</span> {{ email }} <br />
      <span>Gender:</span> {{ gender }} <br />
      <span>ip:</span> {{ ip_address }}
    </div>
  </li>
  <!-- <div class="kewhfb">+</div> , "first_name", "last_name", "email", "gender", "ip_address-->
</template>

<script>
export default {
  props: ["id", "first_name", "last_name", "email", "gender", "ip_address"],
};
</script>

<style>
.list__item {
  display: flex;
  font-family: serif;
  border: 1px solid #000;
  padding: 10px;
  margin-bottom: 15px;
  list-style-type: none;
}
.list__item strong {
  margin-right: 15px;
  font-size: 20px;
}
.list__item span {
  font-size: 20px;
  text-decoration: underline;
  margin-right: 7px;
}
</style>