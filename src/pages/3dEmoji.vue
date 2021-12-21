<template>
  <div class="All-box">
    <div class="First-box">
      <div class="flex justify-between q-pt-md q-mr-lg q-ml-lg">
        <b><span class="text-h6 text-weight-bold">Emoj!</span> by 00</b>
        <b>for figma and blender</b>
        <q-btn color="white"><b style="color: #1D1D1D">Try demo</b></q-btn>
      </div>
      <div>
        <h1 class="q-header text-weight-bold q-mb-lg" style="position: absolute; z-index: 1">emoj!</h1>
        <div class="emoji-set1">
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-1.png?versionId=vuOEA43TMXMGRIQtT7v30EhvrgITrb61"
                 style="width: 30vw; z-index: 2"
          />
          <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-4.png?versionId=IuEBrCtmDJzsy.tfc8xnGOnYEFrpJZQ9"
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
          <div class="justify-center" style="border: 1px solid black">
            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-2.png?versionId=XKPMsbPWA7Ok3gSXj9wDnoXDqtL7Ws1b"
                   style="width: 40vw"
            />
            <q-img src="https://d17v9ds8p1uxd3.cloudfront.net/img_emoji/emoji-5.png?versionId=7SwZD31FqyRsx.YFCC64ae6iuU904Xfm"
                   style="width: 15vw"
            />
          </div>
          <div class="justify-center" style="border: 1px solid black">
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


    <div class="text-center">
      <h3 class="text-weight-bold">Engage your customers</h3>
      <label style="font-size: larger">It's hard to pass through emoji pic and not to stop at<br/>
      ti. Emoji is a famous symbol known worldwide
      </label>
    </div>

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

    <div class="text-center" style="margin-top: 8vw;">
      <p>Main features:</p>
      <h1 class="text-weight-bold">High quality</h1>
    </div>
    <div style="display: flex; justify-content: space-around"><div></div><h1 class="text-weight-bold">Figma file</h1></div>
    <div class="text-center"><h1 class="text-weight-bold">Changeable colors</h1></div>
    <div style="display: flex; justify-content: space-around"><div></div><h1 class="text-weight-bold q-mr-lg">Blender file</h1></div>

  </div>
</template>

<script>
export default {
  name: "3dEmoji"
}
</script>

<style scoped>
.All-box::-webkit-scrollbar{
  width: 10px;
  background: black;
}
.All-box::-webkit-scrollbar-thumb{
  background-color: black;
  border-radius: 10px;
}
.All-box::-webkit-scrollbar-track{
  background-color: red;
  border-radius: 10px;
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
