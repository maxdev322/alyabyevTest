<template>
  <li class="list__item">
    <strong>{{ id }}.</strong> {{ first_name }} {{ last_name }} <br />
    {{ email }} <br />
    Gender: {{ gender }}
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
  border: 1px solid #000;
  padding: 10px;
  margin-bottom: 15px;
  list-style-type: none;
}
.list__item strong {
  font-size: 20px;
}
</style>