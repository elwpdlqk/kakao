<template>
    <ul class="list">
        <li v-for="item in items">
          <img :src="item.imgUrl">
          <h1>{{item.title}}</h1>
          <p>{{item.text}}</p>
          <span>{{item.time}}</span>
        </li>
    </ul>
</template>

<script>
export default {
  data: function () {
    return {
      items: [
        {title: '고구마', imgUrl: 'http://img2.sbs.co.kr/img/sbs_cms/CH/2016/04/18/CH66794991_w300_h300.jpg', text: '안녕', time: '오전 8:30'},
        {title: '감자', imgUrl: 'http://img2.sbs.co.kr/img/sbs_cms/WE/2016/02/15/WE62816895_w300.jpg', text: '오늘의 날씨', time: '오전 7:30'},
        {title: '메밀', imgUrl: 'http://cfile24.uf.tistory.com/image/15733D454EFE68C1026207', text: '물한잔 먹을때', time: '오전 5:30'},
        {title: '당근', imgUrl: 'https://blog.fotolia.com/kr/files/2017/02/Fotolia_110632460_S_copyright-1.jpg', text: '저녁밥 먹자', time: '오전 3:30'},
        {title: '당근', imgUrl: 'https://gsa.kaist.ac.kr/files/attach/images/2946/967/042/3961beab55ae215aaa98f8abf0b4d63d.png', text: '점심밥 먹자', time: '오전 2:30'},
        {title: '당근', imgUrl: 'http://ppss.kr/wp-content/uploads/2015/11/Max-Rive.jpg', text: '아침밥 먹자', time: '오전 1:30'}
      ]
    }
  }
}
</script>

<style>
  li {
    position: relative;
    height: 50px;
    background: #fff;
    border-bottom: 1px solid #dbdbdb;
    font-weight: bold;
    text-align: left;
    padding-left: 80px;;
  }
  img {
    position: absolute;
    width: 50px;
    height: 50px;
    left: 10px;
    border-radius: 50%;
  }
  h1 {
    font-size: 1.3em;
  }
  p {
    font-size: 0.8em;
  }
  li span {
    position: absolute;
    right: 5px;
    top: 5px;
    font-size: 0.7em;
    color: #999;
  }
</style>
