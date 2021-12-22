<template>
  <div id="main">
  <div class="All-box scroll-y" v-scroll:#main="handleScroll" style="max-height: calc(100vh - 50px)" >
    <div class="First-box">
      <div class="flex justify-between q-pt-md q-mr-lg q-ml-lg">
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_main/Eyes.svg?versionId=xgP4ORkrWUfzByergsTzIuFt6mIjt8UO" width="2vw" />
        <b>for figma and blender</b>
        <q-btn color="white"><b style="color: #1D1D1D">Try demo</b></q-btn>
      </div>
      <div class="relative-position">
        <h1 class="q-header text-weight-bold q-mb-lg" style="position: absolute; z-index: 1">emoj!</h1>
        <div class="emoji-set1">
          <q-img id="hornSmile" class="em1" src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-1.png?versionId=vuOEA43TMXMGRIQtT7v30EhvrgITrb61"
                 style="width: 30vw; z-index: 2"
          />
          <q-img id="nerd" class="em2" src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-4.png?versionId=IuEBrCtmDJzsy.tfc8xnGOnYEFrpJZQ9"
                 style="width: 31vw; z-index: 2"
          />
        </div>

      </div>
      <div>
        <div class="text-center" style="line-height: 10px">
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/crown.svg?versionId=eY4rPMmX1ZIXvvK.A8dHRQyhiyPajRSf"
                 width="2.5vw"
          />
          <div class="text-center">
           <span>
             Set of <br/>
             3d emojis for <br/>
             designers and <br/>
             marketers
           </span>
          </div>
          <div class="justify-center">
            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-2.png?versionId=XKPMsbPWA7Ok3gSXj9wDnoXDqtL7Ws1b"
                   style="width: 40vw"
            />
            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-5.png?versionId=7SwZD31FqyRsx.YFCC64ae6iuU904Xfm"
                   style="width: 15vw"
            />
          </div>
          <div class="justify-center">
            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-3.png?versionId=CgASTISBmMafQDCZ12wGs_gkun7l2gzr"
                   style="width: 15vw"
            />

            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-6.png?versionId=R7lYUbtrsYn689Cv72Th3bcY_e0pBz5y"
                   style="width: 35vw"
            />
          </div>
        </div>
      </div>
    </div>

    <!--  퍼스트 박스 끝  -->
    <div class="text-center">
      <h3 class="text-weight-bold">Engage your customers</h3>
      <label style="font-size: larger">It's hard to pass through emoji pic and not to stop at<br/>
      ti. Emoji is a famous symbol known worldwide
      </label>
    </div>
    <!--  세컨드 박스 시작  -->
    <div class="Second-box">

        <div class="text-right"><p>social posts</p></div>
      <div style="display: flex; flex-direction: column; align-items: center; justify-content: space-between">
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-1-p-500.png?versionId=upAHRV5zAevzo9CaIyvsSKdJLLUTtgJk"
          width="25vw" style="margin-bottom: 14vw"
        />
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-2-p-800.png?versionId=gbtbNQiBVNqJjqv5cBbAJlfVKdD1rCnV"  width="25vw" style="margin-bottom: 14vw"/>
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-3-p-500.png?versionId=Lx_OsGnO6dVsiE7A0RdWB5kdM6vEUUFP"  width="25vw" style="margin-bottom: 8vw"/>
      </div>
    </div>

<!--  세컨드 박스 끝  -->
    <div class="text-center" style="margin-top: 8vw;">
      <p>Main features:</p>
      <h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji.png?versionId=R7hp.vcHJy4uUHIzucsE5itzhNjjhTkT" width="6vw" class="q-mr-md"/>High quality</h1>
    </div>
    <div style="display: flex; justify-content: space-around"><div></div><h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-2.png?versionId=HevdBu1cfgfzUXVjg9SHeT96U1HFZ5GC" width="6vw" class="q-mr-md"/>Figma file</h1></div>
    <div class="text-center"><h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-3-4.png?versionId=r807msRDsr4E9zlDevQTECyXQjqrxB4V" width="6vw" class="q-mr-md"/>Changeable colors</h1></div>
    <div style="display: flex; justify-content: space-evenly"><div></div><h1 class="text-weight-bold q-mr-lg"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-4.png?versionId=rhE0de_Q3_oGPTxefIOJxgVXknb6.1S9" width="6vw" class="q-mr-md"/>Blender file</h1></div>

    <!--  서드 박스 시작  -->

    <div class="Third-box">
      <div class="text-center" style="padding-top: 15vw;">
        <h3 class="text-weight-bold">We've tried <br/>
        to pay attention to<br/>
          every<br/>
          little detail
        </h3>
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/Pile-of-Poo-p-800.png?versionId=NJjr1nT3.mzMRQK93VFINrp0tYZ5NNoC" width="24vw" />
      </div>
    </div>

    <!--  포스박스 시작  -->
<div class="Forth-box">
  <div class="text-center">
    <h3>Where to use</h3>
    <p>Perfect for apps, stories and promo websites.</p>
  </div>

  <div class="flex justify-between" style="max-width: 1400px; margin: 0 auto;">
    <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/screen-2.png?versionId=FHC9ktZYWKlsq.V4zUcr0JDUexrUaYpH" width="15vw" />
    <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/screen-3.png?versionId=ZXmUkcXurT0uncnU5Oo2ZMy.jcv4ghh1" width="15vw" />
    <div></div>
    <div></div>
    <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/smile.png?versionId=PlzPAn..2EQ2qDe5gumpStVp0LARVZpS" width="3vw" height="3vw" style="margin-top: 20%" />
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </div>

  <div class="text-center flex justify-evenly" style="max-width: 1400px; margin: 0 auto; margin-bottom: 5vw">
    <div style="display: flex; flex-direction: column; justify-content: center">
      <p style="align-self: center; font-size: x-large">Make your audience smile <br/>
        and fell better connected <br/>
        to your brand with <br/>
        expressive illustations
      </p>
    </div>

    <div>
      <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/screen-1.png?versionId=GV8okn2ihT_hXyk5J14o0W8bU3yig1_e" width="15vw" />
    </div>
  </div>

  <div class="flex justify-center">
    <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/Desktop-6-p-1600.png?versionId=CnexXialDNu3Qr0gtubY3WQedJfaFPtL" width="73vw" style="margin-bottom: 5vw"/>
    <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/Desktop-5-p-1600.png?versionId=BMrXoKbabSJaOCz0Z3XUkV6d9iRbXB5L" width="73vw"/>
  </div>

  <div class="text-center" style="margin-top: 10vw">
    <h2 class="text-weight-bold">How is it going?</h2>
    <p>Find illustration every mood you need. Rate your <br/>
      emotion by clicking the slider
    </p>
  </div>

  <div class="flex justify-center" style="padding-bottom: 10vw">
    <div style="border: 2px solid white; border-radius: 5px">
      <q-img :src="`https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/${faceImgArr[faceStatus]}`" width="15vw"/>
      <q-slider
        v-model="faceStatus"
        snap
        color="white"
        :min="0"
        :max="4"

      />
    </div>

  </div>
</div>

<!-- 포스박스 종료   -->

    <div class="text-center" style="margin-top: 8vw">
      <b>Full preview</b>
      <h1 class="text-weight-bold">36 emojis inside</h1>
    </div>

    <div class="Emoji-box">

      <div style="display: flex; flex-direction: column">
        <div v-for="emoji in emojiArr1" style="text-align: center; margin-bottom: 5vw;">
          <q-img class="justify-between" :src="emoji.image" style="width: 12vw;"/>
          <br/>
          <span style="font-size: x-large">{{emoji.face}}</span>
        </div>
      </div>

      <div style="display: flex; flex-direction: column">
        <div v-for="emoji in emojiArr2" style="text-align: center; margin-bottom: 5vw;">
          <q-img class="justify-between" :src="emoji.image" style="width: 12vw;"/>
          <br/>
          <span style="font-size: x-large">{{emoji.face}}</span>
        </div>
      </div>

      <div style="display: flex; flex-direction: column">
        <div v-for="emoji in emojiArr3" style="text-align: center;margin-bottom: 5vw;">
          <q-img  class="justify-between" :src="emoji.image" style="width: 12vw;"/>
          <br/>
          <span style="font-size: x-large">{{emoji.face}}</span>
        </div>
      </div>

      <div style="display: flex; flex-direction: column">
        <div v-for="emoji in emojiArr4" style="text-align: center; margin-bottom: 5vw">
          <q-img  class="justify-between" :src="emoji.image" style="width: 12vw;"/>
          <br/>
          <span style="font-size: x-large">{{emoji.face}}</span>
        </div>
      </div>

    </div>
<!-- 이모지 박스 끝   -->

    <div class="flex justify-center">
      <svg width="18" height="98" viewBox="0 0 18 98" fill="none" xmlns="http://www.w3.org/2000/svg" style="margin-bottom: 1vw" >
        <path id="arrow-2" d="M9.99992 1C9.99992 25.2593 12.2419 50.8149 9.49992 74.9444C9.18996 77.6721 10.7396 99.2595 5.49992 89.9444C4.23584 87.6972 3.36699 85.2897 2.22214 83C0.767103 80.0899 4.54488 89.0899 5.99992 92C6.55651 93.1132 8.12891 98.7295 9.22214 95.7778C11.8033 88.8086 14.0127 81.8278 16.9999 75" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="stroke-dasharray: 142.674; stroke-dashoffset: 0;"></path>
      </svg>
    </div>
    <div class="text-center">
      <h3>Purchase once and get<br/>
        free update forever!
      </h3>
    </div>

    <div class="item" data-aos="flip-up">1</div>


<!-- fifth박스 시작   -->
    <div class="Fifth-box">
      <div class="tryBox">
        <div>
          <h1 class="text-weight-bold">Try</h1>
        </div>
        <div>
          <ul style="font-size: x-large">
            <li>High resolution</li>
            <li>Changeable colors</li>
            <li>2 emojis</li>
            <li>PNG images</li>
          </ul>
        </div>

        <div style="margin-top: 4vw; margin-bottom: 4vw">
          <q-btn class="q-px-xl q-py-md" outline style="border-radius: 15px">Free download</q-btn>
        </div>
      </div>

      <div class="fullBox">
        <div>
          <h1 class="text-weight-bold">Full</h1>
        </div>
        <div>
          <ul style="font-size: x-large">
            <li>High resolution</li>
            <li>Changeable colors</li>
            <li>36 emojis</li>
            <li>PNG images</li>
            <li>Blender, ready to render</li>
            <li>Figma file</li>
            <li>Free updates</li>
          </ul>
        </div>
        <div style="margin-top: 4vw; margin-bottom: 4vw">
          <q-btn class="q-px-xl q-py-md" style="border-radius: 15px;background-color: #FFC315">Purchase, $24</q-btn>
        </div>
      </div>
    </div>

<!-- 푸터박스 시작   -->
    <div class="footerBox">
      <div class="footerLeft">
        <div>
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_main/logo.svg?versionId=g1VVS.s3v_ZYrQp27.5WfYUSMmHsgWtq" width="10vw" />
        </div>
        <div>
          <p class="text-grey-5">ⓒ2021All Rights Reserved</p>
        </div>
      </div>

      <div class="footerRight">
        <div style="display: flex; flex-direction: column; justify-content: space-between">
          <div><p class="text-weight-bold">Products</p></div>
          <div>
            <p>New release</p>
            <p>Popular</p>
            <p>Freebies</p>
          </div>
        </div>


        <div>
          <div style="display: flex; flex-direction: column; justify-content: space-between">
            <div><p class="text-weight-bold">Legal info</p></div>
            <div>
              <p>License</p>
              <p>help@wannathis.one</p>
            </div>
          </div>
        </div>


        <div>
          <div style="display: flex; flex-direction: column; justify-content: space-between">
            <div><p class="text-weight-bold">Follow us</p></div>
            <div style="display: flex;" >
              <q-img v-for="icon in iconArr" :src="icon" width="1.3vw" />
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
  </div>
</template>

<script>
export default {
  name: "3dEmoji",

  data(){
    return{
      scrollPosition : 0,

      faceImgArr: [
        'em-16.png?versionId=b23An9MITiPkevuqXz8Xk4CfYzzADY4Z',
        'em-13.png?versionId=CimisY42zeP52kHKiCutmtGB9Zk5IWg2',
        'em-11.png?versionId=jEREte37DA4ogXxMm5LTIP5qK1d0gY2f',
        'em-22.png?versionId=vQ5ta2dYcs58xecOiUoRnGJkfVBnvKJW',
        'em-15.png?versionId=.gEFEZOhXn9uOa_JrnLDw5tGOGn5Lq_o'
      ],
      faceStatus: 0,
      emojiArr1: [
        {face:"Heart-Eyes", image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-15.png?versionId=.gEFEZOhXn9uOa_JrnLDw5tGOGn5Lq_o"},
        {face:"Pouting",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-16.png?versionId=b23An9MITiPkevuqXz8Xk4CfYzzADY4Z"},
        {face:"Squinting",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-17.png?versionId=.BF8g7MvCUQtNIi2XaXjZ7.YNz1trI5r"},
        {face:"Blessed",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-18.png?versionId=PRvQrKxYwIHxBww_DMIBuDu5CET84lGb"},
        {face:"Sleeping",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-19.png?versionId=SFldclLQgNcPWttxj0vhUtZk7BmPZxvp"},
        {face:"Winking",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-22.png?versionId=vQ5ta2dYcs58xecOiUoRnGJkfVBnvKJW"},
        {face:"Laughing",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-1.png?versionId=0ljJkTyvnT2YsRt9jSRJ11o8iNwQTHCh"},
        {face:"Zany Face",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-23.png?versionId=ZsPnX9HSC_39A0RC8mJROoF7BfNNCxqX"},
        {face:"Pile of Poo",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-30.png?versionId=RnP7at68iU_sak9A98BhCMKlrBlQKdtR"},
      ],
      emojiArr2:[
        {face:"Sunglasses",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-11.png?versionId=jEREte37DA4ogXxMm5LTIP5qK1d0gY2f"},
        {face:"Smiling with Horns",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-12.png?versionId=O9b8oHJqugc4_0JmV8KokTuSxeptUlsY"},
        {face:"Thinking",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-13.png?versionId=CimisY42zeP52kHKiCutmtGB9Zk5IWg2"},
        {face:"Rolling Eyes",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-14.png?versionId=fu68ckxzDmvUsCgZcJe7qDicYO.bp_9K"},
        {face:"with Monocle",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-20.png?versionId=fF6Vq2xYNyiIio0c7_19jd58nPyG7Qy0"},
        {face:"Confetti",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-21.png?versionId=n2FAqo5roC33Dyldit046H_GScKPXF3O"},
        {face:"Grinning",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-2.png?versionId=qfeUModWcpXxWmye_LXyoi.HOHz6YhYc"},
        {face:"Dollar-Struck",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-29.png?versionId=kzO4MlDfPaYXz3LFWdkA5xLgTN_YzBoH"},
        {face:"Pointing Right",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-35.png?versionId=tPbH3up8LkN1nlttt0NHROdYIf5sUV6w"},
      ],
      emojiArr3:[
        {face:"Nerd",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-7.png?versionId=zlqCg_pRFKa1Vl1n1oiKPx6xbtMyv7B4"},
        {face:"Winking",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-8.png?versionId=qB8TTTrRhn7DugRDVVaI7EnloLPtey20"},
        {face:"Partying",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-9.png?versionId=JQXaAFuUTf4xhc07hvOi5JlRrXpgVtRv"},
        {face:"Angry with Horns",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-10.png?versionId=wx5Y_J9.s_yVFhZfAwLdoYWCRP2yYhE_"},
        {face:"Hugging",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-24.png?versionId=Dzmo6I30IS_Zj3UxDcqRkjSW1a5EUU3f"},
        {face:"Clap",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-28.png?versionId=i8liLxNuwggK_sWo4Zy6IRKPaXa7F_er"},
        {face:"Swearing",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-3.png?versionId=QNUjGdu_LwrEUkHKxGlnXFeO3e7CAizz"},
        {face:"Robot",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-31.png?versionId=KkxwstiX2hD8e2CEDP7lfnIvVt1h_T1Q"},
        {face:"Sign of the Horns",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-34.png?versionId=uylc1ISRxLbXAyFGZYzTR822Fns6o8vz"},
      ],
      emojiArr4:[
        {face:"Star-Struck",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-4.png?versionId=zy3TPV.Rn7o4kvYxAfRfPC_ytvj2Guxy"},
        {face:"Dizzy",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-5.png?versionId=9qfSFzzSmMcIjE1B7VVNtVMVhnwDlqlZ"},
        {face:"Smiling with Hearts",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-6.png?versionId=.EA1vZPzTdVf8V3nbzRlVuYw3CnUXbuL"},
        {face:"Sad",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-27.png?versionId=cihiGYC_h4.xientObx06H9boYU.ZDQ4"},
        {face:"Kissing",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-25.png?versionId=Msi3Uym5X1_Dl328k73anx75a21cde50"},
        {face:"Cookies",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-36.png?versionId=DZ0viCkYTayeO9nXjVTwRopo9C56pc2."},
        {face:"Grinning",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-26.png?versionId=jZCECbXKOYKmh.WOQ4iZ7lnSZ8EnGWHb"},
        {face:"Rainbow",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-32.png?versionId=Rtgz45Cbheg85XMNCsRbL.QLLJ7micvK"},
        {face:"Pointing up",image:"https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/em-33.png?versionId=Xgrm40dx_gU1IiL8jQCIvt3QbLXObbmn"}
      ],
      iconArr:[
        "https://d17v9ds8p1uxd3.cloudfront.net/img_main/ic_behance.svg?versionId=RKDRGU4U1NbRKApJUz2JaQ.GV2LE9liC",
        "https://d17v9ds8p1uxd3.cloudfront.net/img_main/ic_dribbble.svg?versionId=IQReDzkBXlk9BkTSJq1iF7y0kEg5MZYo",
        "https://d17v9ds8p1uxd3.cloudfront.net/img_main/ic_producthunt.svg?versionId=zw2SbwFXUwzQlju_D2HSCoojzlEtOlqC",
        "https://d17v9ds8p1uxd3.cloudfront.net/img_main/ic_twitter.svg?versionId=nCIZLRgiMoHKTBhP_hK3P_zuIl2xOjfW"
      ]
    }
  },
  watch: {

  },
  methods: {
    handleScroll(e){
      console.log(e)
      this.scrollPosition = e;

      if(this.scrollPosition === 100) {
        console.log("hello")
        document.getElementById("hornSmile").classList.add("emoji1")

      }else if( this.scrollPosition === 200){
        document.getElementById("nerd").classList.add("emoji1")
        console.log("down")
      }
    }
  }

}
</script>

<style scoped>
.All-box{
  width: 100%;
  overflow-x: hidden;
}
.All-box::-webkit-scrollbar{
  width: 10px;
}
.All-box::-webkit-scrollbar-thumb{
  background-color: white;
  border-radius: 10px;
}
.All-box::-webkit-scrollbar-track{
  background-color: #936DFC;
}
.First-box{
  width: 100%;
  background: #936DFC;
}
.First-box .q-header{
  color: #8248ff;
  font-size: 24vw;
  text-transform: uppercase;
  line-height: 360px;
  letter-spacing: -38px;
}
.Second-box{
  width: 100%;
  will-change: background;
  background-color: rgb(98, 167, 248);
}
.Third-box{
  width: 100%;
  background: #936DFC;
}
.Forth-box{
  width: 100%;
  background: rgb(222,218,229);
}
.Emoji-box{
  max-width: 1200px;
  display: flex;
  margin: 0 auto;
  justify-content: space-between;
  margin-bottom: 2vw;
}
.Fifth-box{
  max-width: 1200px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  margin-bottom: 6vw;
}
.tryBox{
  width: 48%;
  border: 1px solid black;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
.fullBox{
  width: 48%;
  border-radius: 15px;
  background-color: #936DFC;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
.footerBox{
  max-width: 90%;
  height: 8vw;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}
.footerLeft{
  width: 50%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: start;
  justify-content: space-between;
}
.footerRight{
  width: 50%;
  height: 100%;
  display: flex;
  justify-content: space-around;
}


.q-header.text-weight-bold{
  position: absolute;
  top: 0;
  left: 50%;
  transform: translate(-50%, -50%);
}

.emoji-set1{
  display: flex;
  justify-content: space-around;

}

.text-center span{
  font-size: 5vw;
  line-height: 80%;
}

.emoji1{
  transition-property: transform;
  transform: translateY(200px);
  transition-duration: 0.5s;
  transition-timing-function: ease-in-out;
}

</style>
