<template>
  <div class="page-container feedback-page-container">

    <div class="help-info-item description">
      PicX，基于 GitHub API 搭建的图床神器，图片外链自动使用 jsDelivr 进行 CDN 加速，免费、稳定、高效。
      <br>
      只需一个 GitHub 账号，免下载安装，打开网站即可使用，轻松解决图床难题。
      <br>
      建议将此网站添加至收藏夹，方便下次使用 😊
    </div>

    <div class="help-info-item">
      任何问题请前往：https://github.com/XPoet/picx
      <br>
      本项目不作任何回答
    </div>

    <div class="help-info-item">
      声明：请勿通过此网站上传违反你当地法律的图片，一切后果与此网站无关。
    </div>
  </div>
</template>

<script>

export default {
  name: "Help",
}
</script>

<style scoped lang="scss">

.feedback-page-container {

  .help-info-item {
    font-size: 15.8px;
    padding: 6px;
    display: flex;
    align-items: center;
    margin-bottom: 10px;

    &:last-child {
      margin-bottom: 0;
    }


  }

  .description {
    font-weight: bold;
    line-height: 28px;
  }

  .red-text {
    color: #de1a1a;
  }
}

</style>