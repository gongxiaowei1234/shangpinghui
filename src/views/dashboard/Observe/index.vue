<template>
  <div>
    <el-row :gutter="10">
      <el-col :span="12">
       <Search></Search>
      </el-col>
      <el-col :span="12"> <Category></Category></el-col>
    </el-row>
  </div>
</template>

<script>
import Search from "./Search";
import Category from "./Category";


export default {
  components: {
    Search,
    Category,
  },
  name: "",
  data() {
    return {};
  },
  created() {},
  methods: {},
  mounted() {},
};
</script>

<style>
</style>