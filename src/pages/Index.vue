<template>

  <div>
    <div>

        <header >
          <div class="headerInBox">
            <div class="flex justify-end q-mb-0">
              <span><q-img :src="url" style="width: 32px; height: 32px" /></span>
              <span style="margin-left: 20px"><q-img :src="url" style="width: 32px; height: 32px" /></span>
              <span style="margin-left: 20px"><q-img :src="url" style="width: 32px; height: 32px" /></span>
              <span style="margin-left: 20px"><q-img :src="url" style="width: 32px; height: 32px" /></span>
            </div>
            <div class="flex justify-between q-mb-md">
              <div class="npoLeft">
                <q-img :src="url" style="width: 125px; height: 75px" />
              </div>

              <div class="npoMiddle" @click="isShow = !isShow" style="display: flex; align-items: flex-end">
<!--                <span class="headerNav">센터소개</span>
                <span class="headerNav">센터소식</span>
                <span class="headerNav">NPO정보</span>
                <span class="headerNav">아카이브</span>-->
                <ul class="header_gnb">
                  <li class="text-weight-bold text-h6" style="position: relative; float: left;">센터소개
                  <ul class="header_submenu" style="display: none; opacity: 1">
                    <li>기관소개</li>
                    <li>CI소개</li>
                    <li>일하는 사람들</li>
                    <li>찾아오시는 길</li>
                  </ul>
                  </li>
                  <li class="header_menu text-weight-bold text-h6">센터소식
                    <ul class="header_submenu" style="display: none; opacity: 1">
                      <li>센터소식</li>
                      <li>지원사업</li>
                    </ul>
                  </li>
                  <li class="header_menu text-weight-bold text-h6">NPO정보
                    <ul class="header_submenu" style="display: none; opacity: 1">
                      <li>NPO소식</li>
                      <li>NPO즐겨찾기</li>
                    </ul>
                  </li>
                  <li class="header_menu text-weight-bold text-h6">아카이브
                    <transition name="slide">
                      <ul class="header_submenu" style="display: none; opacity: 1">
                        <li>센터발간자료</li>
                        <li>동북권 아카이브</li>
                        <li>-강북</li>
                        <li>-노원</li>
                        <li>-도봉</li>
                        <li>-성북</li>
                        <li>-중랑</li>
                        <li>타기관NPO자료</li>
                      </ul>
                    </transition>

                  </li>
                  <li class="header_menu text-weight-bold text-h6">공간대관
                    <ul class="header_submenu" style="display: none; opacity: 1">
                      <li>대관안내</li>
                      <li>대관현황</li>
                      <li>사용신청 안내</li>
                      <li>사용 신청서 작성</li>
                    </ul>
                  </li>
                </ul>

              </div>

              <div class="npoRight" style="display: flex; align-items: flex-end">
                <span style="margin-right: 10px">로그인</span>
                <span>/</span>
                <span style="margin-left: 10px">회원가입</span>
              </div>



              <div class="npoRight" style="display: flex; align-items: flex-end">
                <span class="text-weight-bold" style="color: #21BA45">Search</span>
                <q-icon name="search" size="30px" color="green-4" />
              </div>
            </div>
          </div>
        </header>


<!-- 헤더 끝 -->
      <div style="display: flex; justify-content: center; align-items: center;">
<!--        <VueSlickCarousel style="width: 1200px;" v-bind="settings">
          <div><q-img :src="slideUrl1"/></div>
          <div><q-img :src="slideUrl2"/></div>
        </VueSlickCarousel>-->
        <swiper class="swiper" :options="swiperOption">
          <swiper-slide><q-img :src="slideUrl1"/></swiper-slide>
          <swiper-slide><q-img :src="slideUrl2"/></swiper-slide>
          <div class="swiper-pagination" slot="pagination"></div>
          <div class="swiper-button-prev" slot="button-prev"></div>
          <div class="swiper-button-next" slot="button-next"></div>
        </swiper>

      </div>
      <div id="example-3">
        <button @click="show = !show">
          Toggle
        </button>
        <transition
          name="custom-classes-transition"
          enter-active-class="animated tada"
          leave-active-class="animated bounceOutRight"
        >
          <p v-if="show">hello</p>
        </transition>

      </div>


      <div class="mainBody">
        <div class="top flex justify-between q-mt-xl">

          <div style="width: 48.5%">
            <div style="display: flex; justify-content: space-between">
              <p class="text-h5 text-weight-bold">센터소식</p>
              <p class="text-weight-bold text-grey" style="text-align: right">더보기<q-icon name="add" color="purple-9" size="30px" /></p>
            </div>

            <q-separator color="green-4" size="2px"/>

            <q-list class="centerList q-list--dense">
              <q-item class="centerNews">
                <q-item-section>
                  <q-item-label class="text-weight-bold">센터소식</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                </q-item-section>
                <q-item-section side>
                  <q-item-label caption>2021-12-07</q-item-label>
                </q-item-section>
              </q-item>

              <q-separator spaced inset/>

              <q-item class="centerNews">
                <q-item-section>
                  <q-item-label class="text-weight-bold">센터소식</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                </q-item-section>
                <q-item-section side>
                  <q-item-label caption>2021-12-07</q-item-label>
                </q-item-section>
              </q-item>

              <q-separator spaced inset/>

              <q-item class="centerNews">
                <q-item-section>
                  <q-item-label class="text-weight-bold">센터소식</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                </q-item-section>
                <q-item-section side>
                  <q-item-label caption>2021-12-07</q-item-label>
                </q-item-section>
              </q-item>

              <q-separator spaced inset/>

              <q-item class="centerNews">
                <q-item-section>
                  <q-item-label class="text-weight-bold">센터소식</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                </q-item-section>
                <q-item-section side>
                  <q-item-label caption>2021-12-07</q-item-label>
                </q-item-section>
              </q-item>

              <q-separator spaced inset/>

              <q-item class="centerNews">
                <q-item-section>
                  <q-item-label class="text-weight-bold">센터소식</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                </q-item-section>
                <q-item-section side>
                  <q-item-label caption>2021-12-07</q-item-label>
                </q-item-section>
              </q-item>

              <q-separator spaced inset/>

            </q-list>
          </div>



          <div style="width: 48.5%">
            <div style="display: flex; justify-content: space-between">
              <p class="text-h5 text-weight-bold">NPO소식</p>
              <p class="text-weight-bold text-grey" style="text-align: right">더보기<q-icon name="add" color="purple-9" size="30px" /></p>
            </div>

            <q-separator color="green-4" size="2px"/>


            <div>
              <q-list class="npoList q-list--dense">
                <q-item class="npoNews">
                  <q-item-section>
                    <q-item-label class="text-weight-bold">NPO소식</q-item-label>
                  </q-item-section>
                  <q-item-section>
                    <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                  </q-item-section>
                  <q-item-section side>
                    <q-item-label caption>2021-12-07</q-item-label>
                  </q-item-section>
                </q-item>

                <q-separator spaced inset/>

                <q-item class="npoNews">
                  <q-item-section>
                    <q-item-label class="text-weight-bold">구인</q-item-label>
                  </q-item-section>
                  <q-item-section>
                    <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                  </q-item-section>
                  <q-item-section side>
                    <q-item-label caption>2021-12-07</q-item-label>
                  </q-item-section>
                </q-item>

                <q-separator spaced inset/>

                <q-item class="npoNews">
                  <q-item-section>
                    <q-item-label class="text-weight-bold">구인</q-item-label>
                  </q-item-section>
                  <q-item-section>
                    <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                  </q-item-section>
                  <q-item-section side>
                    <q-item-label caption>2021-12-07</q-item-label>
                  </q-item-section>
                </q-item>

                <q-separator spaced inset/>

                <q-item class="npoNews">
                  <q-item-section>
                    <q-item-label class="text-weight-bold">NPO소식</q-item-label>
                  </q-item-section>
                  <q-item-section>
                    <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                  </q-item-section>
                  <q-item-section side>
                    <q-item-label caption>2021-12-07</q-item-label>
                  </q-item-section>
                </q-item>

                <q-separator spaced inset/>

                <q-item class="npoNews">
                  <q-item-section>
                    <q-item-label class="text-weight-bold">NPO소식</q-item-label>
                  </q-item-section>
                  <q-item-section>
                    <q-item-label class="text-weight-bold" style="color: black">2021 그룹워킹데이</q-item-label>
                  </q-item-section>
                  <q-item-section side>
                    <q-item-label caption>2021-12-07</q-item-label>
                  </q-item-section>
                </q-item>

                <q-separator spaced inset/>

              </q-list>
            </div>
          </div>
        </div>

<!--  #############구분선######################      -->

        <div class="flex justify-between q-mb-lg" >
          <div style="width: 48.5%">
              <div style="display: flex; justify-content: space-between">
                <p class="text-h5 text-weight-bold">아카이브</p>
                <p class="text-weight-bold text-grey" style="text-align: right">더보기<q-icon name="add" color="purple-9" size="30px" /></p>
              </div>

            <q-separator color="green-4" size="2px"/>


            <div class=" q-mt-lg" style="display: flex; justify-content: space-between">
              <div class="q-mr-lg">
                <q-img :src="url" style="width: 250px; height: 350px;" />
                <p class="text-weight-bold" style="font-size: larger">커피와 영화가 만나는 곳 빈스로드</p>
              </div>
              <div>
                <q-img :src="url" style="width: 250px; height: 350px;"/>
                <p class="text-weight-bold" style="font-size: larger">성북청년시민회 한해살이 2021-<br/>우리가 서로의 비빌언덕이 될 수...</p>
              </div>
            </div>


              <div style=" width: 100%">
                <div style="border: 1px solid #b0b0b0; padding: 15px 15px">
                  <p style="color: #615097; font-weight: bolder; font-size: larger">시설이용 신청</p>
                </div>

                <div  style="background: #615097; padding: 15px 15px;">
                  <span style="color: white; font-weight: bold; font-size: larger">동북권 NPO센터의 이용 가능한 시설들을 알려드립니다.  </span>
                </div>
              </div>
          </div>


          <div style="width: 48.5%">
            <q-img
                  :src="url"
                 />
          </div>
        </div>

        <div style="text-align: center">
          <span class="text-h5 text-weight-bold">NPO즐겨찾기</span>
          <q-separator class="q-mb-sm" color="white" />
          <div style="margin: 0 auto; width: 10%; border-top: 2px solid #11b466"></div>
          <q-img
            v-for="transition in transitions"
            :key="transition"
            :transition="transition"
            :src="url"
            style="width: 125px; height: 60px;"
            ratio="1"
            class="q-mr-md q-mt-md q-mb-lg"
          >
            <div class="absolute-bottom text-center text-body2">{{transition}}</div>
          </q-img>
        </div>
      </div>
    </div>


    <div class="newsBox q-pt-xl q-pb-xl">
      <span class="text-h5 text-weight-bold">뉴스레터를 받아보세요</span>
      <q-separator class="q-mb-sm" color="#f5f5f5" style="background: #f5f5f5" />
      <div style="margin: 0 auto; width: 10%; border-top: 2px solid #615097"></div>
      <div class="q-mt-md">
        <span class="text-grey">서울시 동북권의 NPO소식을 이메일로 편하게 받아보세요</span>
      </div>

      <div class="q-mt-md">
        <q-checkbox v-model="val"><span style="text-decoration: underline; color: #11b466">마케팅 정보 수신</span>에 동의합니다.</q-checkbox>
      </div>
      <div class="flex justify-center">
        <div style="width: 50%; display: flex; justify-content: center">

          <q-input class="q-mr-md" outlined v-if="val" style="width: 30%" square dense placeholder="이메일" />
          <q-input class="q-mr-md" outlined v-else-if="val==false" style="width: 30%" square dense readonly placeholder="이메일" />

          <q-input class="q-mr-md" outlined v-if="val" style="width: 10%" square dense placeholder="이름" />
          <q-input class="q-mr-md" outlined v-else-if="val==false" style="width: 10%" square dense readonly placeholder="이름" />

          <q-btn class="q-mb-lg" style="background: #666666; border-radius: 0; color: white"><span style="text-align: center" class="text-weight-bold q-ml-lg">구독하기</span>
            <q-badge rounded color="white" class="q-mb-lg q-ml-md" />
          </q-btn>
        </div>
      </div>


      <span style="text-decoration: underline; font-weight: bold; color: #11b466">지난 뉴스레터 보기</span>
    </div>
    <footer class="footer">
      <div class="footerbox">
        <div>
          <q-img :src="url" style="width: 250px; height: 75px"/>
        </div>

        <div class="footerInfo">
          <span>이용약관 / <a href="#" style="color: yellow; text-decoration: none">개인정보처리방침</a></span><br/>
          <span style="color: #666666">대구광역시 북구 산격동 505-7 소프트웨어벤처타워 904호 / 대충 전화번호 / 대충 팩스 / 대충 이메일</span><br/>
          <span style="color: #666666">©Copyright2021Deagu SOFTWEARTOWER.All rights reserved.</span>
        </div>
      </div>

    </footer>
  </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

import {Swiper, SwiperSlide} from 'vue-awesome-swiper'
import 'swiper/css/swiper.css'
import Vue from "vue";
new Vue({
  el:'#example-3',
  data: {
    show: true
  }
})

export default {
  name: 'PageIndex',
  components: {
    VueSlickCarousel,
    Swiper,
    SwiperSlide
  },
  data(){
    return {
      slideUrl1: 'https://placeimg.com/1200/160/nature',
      slideUrl2: 'https://placeimg.com/1200/160/animals',
      url: 'https://placeimg.com/560/750/nature',
      val: 'true',
      swiperOption: {
        slidesPerView: 1,
        spaceBetween: 30,
        loop: true,
        pagination: {
          el: '.swiper-pagination',
          clickable: true,
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev'
        }
      },
      isShow:false,
      slide: 1,
      settings:{
        slidesToShow: 1,
        slidesToScroll: 1,
        focusOnSelect: true,
        arrows: true,
        dots: true,
        centerMode: true,
        centerPadding: '200px'
      },
      transitions:[
        '1',
        '2',
        '3',
        '4',
        '5',
        '6',
        '7',
        '8'
      ]
    }

  },



}
</script>

<style>
.mainBody{
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
}
.top{
  margin-bottom: 20px;
}
.slider .slick-list{
  margin:0 -20px;
  padding: 0 220px;
}
.slick-slide {
  margin: 0 20px;
}
.slick-track {
  margin-left: auto;
  margin-right: auto;
}
.slider{
  position: relative;
}
.slick-dots li button::before{
  color: grey;
}
.slick-dots li.slick-active button::before{
  color: green;
}
.slide-enter-active{
  -moz-transition-duration: 1s;
  -webkit-transition-duration: 1s;
  -o-transition-duration: 1s;
  transition-duration: 1s;
  -moz-transition-timing-function: ease-in-out;
  -webkit-transition-timing-function: ease-in-out;
  -o-transition-timing-function: ease-in-out;
  transition-timing-function: ease-in-out;
}
.slide-leave-active {
  -moz-transition-duration: 2s;
  -webkit-transition-duration: 2s;
  -o-transition-duration: 2s;
  transition-duration: 2s;
  -moz-transition-timing-function: ease-in-out;
  -webkit-transition-timing-function: ease-in-out;
  -o-transition-timing-function: ease-in-out;
  transition-timing-function: ease-in-out;
}
.slide-enter-to, slide-leave {
  max-height: 500px;
  overflow: hidden;
}

.slide-enter, .slide-leave-to {
  overflow: hidden;
  max-height: 0;
}
.header_gnb{
  float: left;
  margin-bottom: 0;
}
.header_menu{
  position: relative;
  float: left;
  margin-left: 68px;
}
.header_menu::before{
  content: '';
  top: 50%;
  left: -34px;
  position: absolute;
  width: 1px;
  height: 14px;
  margin-top: -7px;
  background: #CCCCCC;
  transform: rotate(45deg);
}
.footerbox{
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  padding-top: 30px;
  padding-bottom: 30px;
  display: flex;
  justify-content: flex-start;
}
.footerInfo{
  margin-left: 30px;
}
.newsBox{
  background: #f5f5f5;
  text-align: center;
}
.centerNews{
  color: #11b466;
  font-weight: bold;
}
.npoNews{
  color: #615097;
  font-weight: bold;
}
.headerInBox{
  width: 100%;
  max-width: 1200px;
}
li{
  display: list-item;
  list-style: none;
}

q-separator{
  margin-top: 0;
}
q-separator::before{
  content: '';
  position: absolute;
  top: -4px;
  width: 6px;
  height: 6px;
  border-radius: 100%;
  background: #009b4e;
}

header{
  width: 100%;
  margin: 0 auto;
  position: sticky;
  padding-top: 20px;
  top: -20px;
  z-index: 1;
  display: flex;
  justify-content: center;
  background: white;
  border-bottom: 1px solid #b0b0b0;
}
footer{
  background: #333333;
  color: #ffffff;
}
</style>
