<template>
<div>
  <div class="hello">
    <h1>Find University Vue</h1>
    <ul>
      <li>
        <dl>
          <dt>学校名称</dt>
          <dd>
            <input type="text">
            <button>Search</button>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt>地区</dt>
          <dd>
            <a href>新南威尔士州</a>
          </dd>
          <dd>
            <a href>昆士兰州</a>
          </dd>
          <dd>
            <a href>南澳州</a>
          </dd>
          <dd>
            <a href>维多利亚州</a>
          </dd>
          <dd>
            <a href>西澳州</a>
          </dd>
          <dd>
            <a href>首府领地</a>
          </dd>
          <dd>
            <a href>北领地</a>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt>QS 排名</dt>
          <dd>
            <a href>1~10名</a>
          </dd>
          <dd>
            <a href>10~20名</a>
          </dd>
          <dd>
            <a href>20~50名</a>
          </dd>
          <dd>
            <a href>50~100名</a>
          </dd>
          <dd>
            <label for="">其他</label>
            <input type="text" oninput=""> ~ <input type="text" oninput=""> 名
            <button>确定</button>
          </dd>
        </dl>
      </li>
    </ul>
  </div>
  <div>
    <div class="head">

    </div>
    <div class="content">
      <ul>

      </ul>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
