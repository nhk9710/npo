<template>
  <div id="app">
    <main class="sticky-container" ref="sticky-container">
    <div class="First-box">
      <div class="flex justify-between q-pt-md q-mr-lg q-ml-lg">
        <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_main/Eyes.svg?versionId=xgP4ORkrWUfzByergsTzIuFt6mIjt8UO" width="2vw" />
        <b>for figma and blender</b>
        <q-btn color="white"><b style="color: #1D1D1D">Try demo</b></q-btn>
      </div>
      <div class="relative-position slide-container">
        <h1 class="q-header text-weight-bold q-mb-lg" style="position: absolute; z-index: 0">emoj!</h1>
        <div class="emoji-set1" >
          <div ref="sl1"><q-img  src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-1.png?versionId=vuOEA43TMXMGRIQtT7v30EhvrgITrb61" style="width: 30vw; "/></div>
          <div ref="sl2"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-4.png?versionId=IuEBrCtmDJzsy.tfc8xnGOnYEFrpJZQ9" style="width: 31vw; "/></div>

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
          <div class="justify-center slide-container">
            <div ref="sl3"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-2.png?versionId=XKPMsbPWA7Ok3gSXj9wDnoXDqtL7Ws1b" style="width: 40vw"/></div>
            <div ref="sl4"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-5.png?versionId=7SwZD31FqyRsx.YFCC64ae6iuU904Xfm" style="width: 20vw"/></div>
          </div>

          <div class="justify-center slide-container" >
            <div ref="sl5"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-3.png?versionId=CgASTISBmMafQDCZ12wGs_gkun7l2gzr" style="width: 15vw"/></div>
            <div ref="sl6"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-6.png?versionId=R7lYUbtrsYn689Cv72Th3bcY_e0pBz5y" style="width: 35vw"/></div>
          </div>
        </div>
      </div>
    </div>

<!--==============================================================================================================================================================-->

      <div class="text-center q-mb-lg" >
        <h3 class="text-weight-bold">Engage your customers</h3>
        <label style="font-size: larger">It's hard to pass through emoji pic and not to stop at<br/>
          ti. Emoji is a famous symbol known worldwide
        </label>
      </div>
<!--===============================================================================================================================================================-->

      <div id="second-box" class="Second-box" ref="sl7">

        <div class="text-right"><p>social posts</p></div>
        <div style="display: flex; flex-direction: column; align-items: center; justify-content: space-between">
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-1-p-500.png?versionId=upAHRV5zAevzo9CaIyvsSKdJLLUTtgJk"
                 width="25vw" style="margin-bottom: 14vw; margin-top: 14vw"
          />
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-2-p-800.png?versionId=gbtbNQiBVNqJjqv5cBbAJlfVKdD1rCnV"  width="25vw" style="margin-bottom: 14vw"/>
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/post-3-p-500.png?versionId=Lx_OsGnO6dVsiE7A0RdWB5kdM6vEUUFP"  width="25vw" style="margin-bottom: 8vw"/>
        </div>
      </div>
<!--=================================================================================================================================================================-->
      <div class="text-center" style="margin-top: 8vw;">
        <p>Main features:</p>
        <div ref="sl8"><h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji.png?versionId=R7hp.vcHJy4uUHIzucsE5itzhNjjhTkT" width="6vw" class="q-mr-md"/>High quality</h1></div></div>
      <div ref="sl9" style="display: flex; justify-content: space-around"><div></div><h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-2.png?versionId=HevdBu1cfgfzUXVjg9SHeT96U1HFZ5GC" width="6vw" class="q-mr-md"/>Figma file</h1></div>
      <div ref="sl10" class="text-center"><h1 class="text-weight-bold"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-3-4.png?versionId=r807msRDsr4E9zlDevQTECyXQjqrxB4V" width="6vw" class="q-mr-md"/>Changeable colors</h1></div>
      <div ref="sl11" style="display: flex; justify-content: space-evenly"><div></div><h1 class="text-weight-bold q-mr-lg"><q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/feature-4.png?versionId=rhE0de_Q3_oGPTxefIOJxgVXknb6.1S9" width="6vw" class="q-mr-md"/>Blender file</h1></div>



    </main>

  </div>
</template>

<script>
import bezierEasing from "bezier-easing";

const ease = bezierEasing(0.25, 0.1, 0.25, 1.0);
const easeIn = bezierEasing(0.38, 0.01, 0.78, 0.13);
const midSlow = bezierEasing(0, 0, .59, 1);

const def = {
  height: 9000,
  elements: {
    sl1: {
      top: 0,
      bottom: 1500,
      topStyle: {
        translateY: -70
      },
      bottomStyle: {
        translateY: 70
      }
    },
    sl2: {
      top: 0,
      bottom: 1500,
      topStyle: {
        opacity: 1,
        translateY: 70
      },
      bottomStyle: {
        opacity: 1,
        translateY: -70
      }
    },
    sl3: {
      top: 500,
      bottom: 2100,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl4: {
      top: 900,
      bottom: 2100,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl5: {
      top: 1000,
      bottom: 2800,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl6: {
      top: 1100,
      bottom: 2800,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl7: {
      top: 2200,
      bottom: 7000,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl8: {
      top: 5000,
      bottom: 7700,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl9: {
      top: 5000,
      bottom: 7700,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl10: {
      top: 5000,
      bottom: 7700,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },
    sl11: {
      top: 5000,
      bottom: 7700,
      topStyle: {
        opacity: 1
      },
      bottomStyle: {
        opacity: 1
      }
    },

  },
  animations: {
    sl1: [
      {
        top: 0,
        bottom: 800,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: -70,
            bottomValue: 70
          }
        }
      },
    ],
    sl2: [
      {
        top: 0,
        bottom: 800,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: 70,
            bottomValue: -70
          }
        }
      },
    ],
    sl3: [
      {
        top: 800,
        bottom: 1600,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: -70,
            bottomValue: 70
          }
        }
      },
    ],
    sl4: [
      {
        top: 900,
        bottom: 1700,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: 60,
            bottomValue: -60
          }
        }
      },
    ],
    sl5: [
      {
        top: 1700,
        bottom: 1900,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: 50,
            bottomValue: -50
          }
        }
      },
    ],
    sl6: [
      {
        top: 1800,
        bottom: 2000,
        easing: midSlow,
        styles: {
          translateY: {
            topValue: -50,
            bottomValue: 50
          }
        }
      },
    ],
    sl7: [
      {
        top: 2200,
        bottom: 3000,
        easing: midSlow,
        styles: {
          scaleX: {
            topValue: 1,
            bottomValue: 1.1
          }
        },
      },
      {
        top: 5000,
        bottom: 6000,
        easing: midSlow,
        styles: {
          scaleX: {
            topValue: 1.1,
            bottomValue: 1
          }
        },
      },
    ],
    sl8: [
      {
        top: 5500,
        bottom: 6500,
        easing: midSlow,
        styles: {
          translateX: {
            topValue: 120,
            bottomValue: -120
          }
        },
      }
    ],
    sl9: [
      {
        top: 5500,
        bottom: 6500,
        easing: midSlow,
        styles: {
          translateX: {
            topValue: 120,
            bottomValue: -120
          }
        },
      }
    ],
    sl10: [
      {
        top: 5600,
        bottom: 6600,
        easing: midSlow,
        styles: {
          translateX: {
            topValue: -120,
            bottomValue: 120
          }
        },
      }
    ],
    sl11: [
      {
        top: 5600,
        bottom: 6600,
        easing: midSlow,
        styles: {
          translateX: {
            topValue: 120,
            bottomValue: -120
          }
        },
      }
    ],


  }
};

let enabled = new Map();
let disabled = new Map();

const isAmong = (num, top, bottom) => num >= top && num <= bottom;

const applyStyle = (element, styleName, value, px = "px", deg="deg", size="") => {
  if (styleName === "translateY") {
    // eslint-disable-next-line no-param-reassign
    element.style.transform = `translateY(${value}${px})`;
    return;
  }
  if (styleName === "translateX") {
    // eslint-disable-next-line no-param-reassign
    element.style.transform = `translateX(${value}${px})`;
    return;
  }
  if (styleName === "scaleX") {
    element.style.transform = `scaleX(${value}${size})`;
    return;
  }
  if (styleName === "scaleY") {
    element.style.transform = `scaleY(${value}${size})`;
    return;
  }
  if (styleName === "scale") {
    element.style.transform = `scaleY(${value}${size})`;
    return;
  }

  // eslint-disable-next-line no-param-reassign
  element.style[styleName] = value;
};

export default {
  name: "testPage",
  data() {
    return {
      message: "Welcome to Vue!"
    };
  },
  mounted() {
    this.init();
    window.addEventListener("scroll", this.onScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.onScroll);
  },

  methods: {
    init() {
      this.initAnimation();
    },
    // 애니메이션 초기화
    initAnimation() {
      // Sticky Conainer 의 높이를 설정함.
      this.$refs["sticky-container"].style.height = `${def.height}px`;

      // disabled, enabled 를 비움.
      disabled.clear();
      enabled.clear();

      // 모든 요소를 disabled 에 넣음.
      for (const refname of Object.keys(def.elements)) {
        disabled.set(refname, def.elements[refname]);
      }

      // 각 애니메이션을 enabled == false 로 만듬.
      for (const refname of Object.keys(def.animations)) {
        for (const animation of def.animations[refname]) {
          animation.enabled = false;
        }
      }

      // 초기 스타일 적용
      disabled.forEach((obj, refname) => {
        Object.keys(obj.topStyle).forEach((styleName) => {
          const pushValue = obj.topStyle[styleName];
          this.$refs[refname].style[styleName] = pushValue;
        });
      });

      // 이미 요소의 범위 및 애니메이션의 범위에 있는 것들을 렌더링하기 위해
      // 임의로 스크롤 이벤트 핸들러를 한 번 실행시킴.
      this.onScroll();
    },
    applyStyles(currentPos, refname, styles, r, px = "px", deg="deg",size="") {
      for (const style of Object.keys(styles)) {
        const { topValue, bottomValue } = styles[style];
        const calc = (bottomValue - topValue) * r + topValue;
        applyStyle(this.$refs[refname], style, calc, px, deg, size);
      }
    },
    applyAllAnimation(currentPos, refname) {
      const animations = def.animations[refname];
      if (!animations) return;
      for (const animation of animations) {
        const { top: a_top, bottom: a_bottom, easing, styles } = animation;
        const isIn = isAmong(currentPos, a_top, a_bottom);
        // 만약 애니메이션이 새롭게 들어갈 때 혹은 나갈때 enabled 설정
        if (isIn) {
          if (!animation.enabled) animation.enabled = true;
        } else if (!isIn && animation.enabled) {
          if (currentPos <= a_top) {
            this.applyStyles(currentPos, refname, styles, 0);
          } else if (currentPos >= a_bottom) {
            this.applyStyles(currentPos, refname, styles, 1);
          }
          // eslint-disable-next-line no-param-reassign
          animation.enabled = false;
        }

        // 애니메이션이 enabled 라면, 애니메이션 적용.
        if (animation.enabled) {
          const r = easing((currentPos - a_top) / (a_bottom - a_top));
          // eslint-disable-next-line no-param-reassign
          this.applyStyles(currentPos, refname, styles, r);
        }
      }
    },
    onScroll() {
      // 현재 스크롤 위치 파악
      const scrollTop = window.scrollY || window.pageYOffset;
      const currentPos = scrollTop + window.innerHeight / 2;

      // disabled 순회하며 활성화할 요소 찾기.
      disabled.forEach((obj, refname) => {
        // 만약 칸에 있다면 해당 요소 활성화
        if (
          isAmong(currentPos, obj.top, obj.bottom)
        ) {
          enabled.set(refname, obj);
          this.$refs[refname].classList.remove("disabled");
          this.$refs[refname].classList.add("enabled");
          disabled.delete(refname);
        }
      });

      // enabled 순회하면서 헤제할 요소를 체크
      enabled.forEach((obj, refname) => {
        const { top, bottom, topStyle, bottomStyle } = obj;
        // console.log(`${top}, ${bottom}, ${topStyle}, ${bottomStyle}`);
        // 범위 밖에 있다면
        if (!isAmong(currentPos, top, bottom)) {
          // 위로 나갔다면 시작하는 스타일 적용
          if (currentPos <= top) {
            Object.keys(topStyle).forEach((styleName) => {
              applyStyle(this.$refs[refname], styleName, topStyle[styleName]);
            });
          }
          // 아래로 나갔다면 끝나는 스타일적용
          else if (currentPos >= bottom) {
            Object.keys(bottomStyle).forEach((styleName) => {
              applyStyle(
                this.$refs[refname],
                styleName,
                bottomStyle[styleName]
              );
              // this.$refs[refname].style[styleName] = bottomStyle[styleName];
            });
          }

          // 리스트에서 삭제하고 disabled로 옮김.
          disabled.set(refname, obj);
          this.$refs[refname].classList.remove("enabled");
          this.$refs[refname].classList.add("disabled");
          enabled.delete(refname);
        }

        // enable 순회중, 범위 내부에 제대로 있다면 각 애니메이션 적용시키기.
        else {
          this.applyAllAnimation(currentPos, refname);
        }
      });
    }
}
  }


</script>

<style scoped>
body {
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
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
  width: 90vw;
  background-color: rgb(98, 167, 248);
  margin: 0 auto;
  border-radius: 30px;
}

.sticky {
  top: 0;
  width: 100%;
  height: 100vh;
}

.slide-container {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
}
.slide {
  position: absolute;
  display: none;
  z-index: 0;
}
.slide.enabled {
  display: block;
}

.slide-big-text p {
  margin: 0;
  font-size: 45px;
  font-weight: bold;
  line-height: 1.35;
  letter-spacing: -1.5px;
  word-spacing: 1.5px;
  text-align: center;
}


.slide-small-text {
  margin-top: 20px;
  margin-left: 5px;
}

.slide-small-text p {
  font-size: 18px;
  margin: 0;
}

.scdown {
  position: absolute;
  padding: 30px 0;
  width: 100%;
  height: 50px;
  text-align: center;
  bottom: 0;
}

.special{
  width: 90vw;
  background-color: black;
  border-radius: 15px;
  border: 1px solid black;
  color: white;
}

.wave{
  background-color: #936DFC;
  width: 90vw;
  color: white;
  border: 1px solid #936DFC;
  border-radius: 15px;
  z-index: -1;
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

</style>
