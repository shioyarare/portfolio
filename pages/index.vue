<template>
  <section class="container">
    <div>
      <h1 class="title">
				shioyarare
      </h1>
      <h2 class="subtitle">
				Portfolio Site
      </h2>
      <div class="links">
        <a
          href="https://github.com/shioyarare"
          target="_blank"
          class="button--grey">GitHub</a>
				<a
					href="https://twitter.com/shioyarare"
					target="_blank"
					class="button--grey">Twitter</a>
				<a
					href="https://atcoder.jp/users/shioya"
					target="_blank"
					class="button--grey">AtCoder</a>
      </div>
			<main class="home">
				<h2>About</h2>
					<li>Name: Shoya HARA </li>
				<h2>Certification</h2>
					<li>ITパスポート </li>
					<li>基本情報技術者資格 </li>
				<h2>Education</h2>
					<li><div class="act_date">2020-03-13</div>都城工業高等専門学校 電気情報工学科 卒業 - 準学士(工学) </li>
					<li><div class="act_date">2020-04-01</div>九州工業大学 情報・通信工学科 入学 </li>
					 - 同大学在学中
				<h2>Works</h2>
					<li> <div class="act_date">2017-06-24</div>第地方創生観光ハッカソン 宮崎ミライHack Days 参加
						<a 
							href="https://connpass.com/event/57371/"
							target="_blank">
							<font-awesome-icon :icon="['fas', 'globe']" />
						</a>
					</li>
					<li> <div class="act_date">2017-10-08</div>第28回 全国高等専門学校プログラミングコンテスト 競技部門 参加 
						<a
							href="http://www.procon.gr.jp/?page_id=59121"
							target="_blank">
							<font-awesome-icon :icon="['fas', 'globe']" />
						</a>
					</li>
					<li> <div class="act_date">2018-02-08</div>第2回 RESAS アプリコンテスト 優秀賞 宮崎地方創成シミュレーションゲーム 輝け☆ミライの観光大使
						<a 
							href="https://opendata.resas-portal.go.jp/contest2nd/index.html"
							target="_blank">
							<font-awesome-icon :icon="['fas', 'globe']" />
						</a>
						<a 
							href="https://www.youtube.com/watch?v=llLZD2AaNoM&feature=emb_logo"
							target="_blank">
    					<font-awesome-icon :icon="['fab', 'youtube']" />
						</a>
					</li>
					<li>都城高専卒業研究「RNNによる小説における人物間の動的感情推定」 </li>
				<h2>Activities</h2>
					<li><div class="act_date">2019-01-17</div>RESASアプリコンテスト意見交換会
						<a 
							href="https://opendata.resas-portal.go.jp/contest3rd/meeting.html"
							target="_blank">
							<font-awesome-icon :icon="['fas', 'globe']" />
						</a>
					</li>
			</main>
			<footer>
				Copyright© shioyarare
			</footer>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>

h2 {
	margin-top: 10px;
	margin-bottom: 6px;
}

footer {
	margin-top: 100px;
	text-align: center;
	justify-content: center;
	display: flex;
	color: gray;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 75px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.home {
	color: #35495e; 
	display: block;
	text-align: left;
	font-size: 16px;
	margin-bottom: 0px;
	margin-left: 0px;
	margin-right: 440px;
	margin-top: 0px;
	max-width: 960px;
	padding-bottom: 0px;
	padding-left: 32px;
	padding-right: 32px;
	padding-top: 60px;
}

.ref-contents {
	display: flex;
	flex-direction: column;
}

.ref-contents li {
	display: inline;
}

.act_date {
	background-color: darkgray;
	padding-left: 5px;
	padding-right: 5px;
	margin-right: 3px;
	display: inline-block;
}
</style>

