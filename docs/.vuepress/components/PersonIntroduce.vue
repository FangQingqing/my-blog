<template>
  <div class="person-wrap">
    <div class="line">
      <div class="person-img">
        <img src="../public/fqq.jpg" />
      </div>
      <div class="person-text">
        <p>姓名：方青青</p>
        <p>花名：子衿</p>
        <p>毕业院校：重庆交通大学</p>
        <p>毕业年份：2017年</p>
        <p>所在公司：中冶赛迪重庆信息技术有限公司</p>
        <p>岗位：前端开发工程师</p>
        <p>所在城市：重庆渝北</p>
        <p>爱好：看书，写字，旅游...</p>
      </div>
    </div>
    <div class="p-detail">个人经历：从小在贵州生活，直到上大学才考到重庆，毕业后直接在这里工作了。以前特别想去一线城市闯荡，觉得年轻就是资本，应该多看看外面的世界，但毕业由于第一份工作留在了重庆，现在再想出去却没有那个勇气了。在前端工作已经两年了，积累了两年的经验，但不知道跟同龄人相比自己的优势在哪里，劣势在哪里，好像有必要好好自我反省一下了。</div>
  </div>
</template>

<script>
export default {
  //
}
</script>

<style lang="scss" scoped>
.personal-wrap {
  width: 100%;
}
.line {
  display: flex;
  justify-content: center;
}
.person-img {
  width: 400px;
  padding-right: 50px;
}
.person-text {
  padding-top: 100px;
}
.person-text p {
  font-size: 16px;
  color: #333;
  line-height: 30px;
}
.p-detail {
  padding-top: 20px;
  line-height: 20px;
  font-size: 14px;
  color: #333;
  text-indent: 2em;
}
</style>
