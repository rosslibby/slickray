<#assign color_scheme = themeDisplay.getColorScheme().getCssClass()>
<#assign dlAppLocalServiceUtil = staticUtil["com.liferay.document.library.kernel.service.DLAppLocalServiceUtil"]>
<#assign dlUtil = staticUtil["com.liferay.document.library.kernel.util.DLUtil"]>
<#assign
  Icon = ""
  Image = ""
  Title = ""
  Subtext = ""
  Tagline = ""
  LinkURL = ""
  LinkText = "">
<section class="carousel">
  <#if entries?has_content>
    <#list entries as curEntry>
      <#assign renderer = curEntry.getAssetRenderer()>
      <#assign className = renderer.getClassName()>
      <#assign journalArticle = renderer.getArticle()>
      <#assign document = saxReaderUtil.read(journalArticle.getContentByLocale(locale))>
      <#assign rootElement = document.getRootElement()>
      <#assign imageJson = document.valueOf("//dynamic-element[@name='Image']/dynamic-content/text()")>
      <#assign Subtext = document.valueOf("//dynamic-element[@name='Subtext']/dynamic-content/text()")>
      <#assign Title = document.valueOf("//dynamic-element[@name='Title']/dynamic-content/text()")>
      <#if imageJson?has_content>
        <#assign
          imageJson = imageJson?eval
          uuid = imageJson.uuid
          groupId = imageJson.groupId
          dlFile = dlAppLocalServiceUtil.getFileEntryByUuidAndGroupId(uuid,groupId?number)
          Image = dlUtil.getPreviewURL(dlFile, dlFile.getFileVersion(),themeDisplay,'')>
      </#if>
      <div>

        <#-- style the carousel -->
        <style>
          /**
           * Style the containing element for the slides
           */
          .slick-slide__wrapper {
            max-width: 1200px;
            display: flex;
            float: none;
            margin: 0 auto;
          }

          /**
           * Style the text container
           */
          .slick-text {
            color: #ffffff;
            text-transform: uppercase;
            position: absolute;
            margin-top: 151px;
          }

          /**
           * Style the heading
           */
          .slick-text__title {
            font-size: 200px;
            letter-spacing: -7px;
            font-family: 'Anton', sans-serif;
            line-height: 169px;
            margin-bottom: 0;
            -webkit-animation: fadein 2s; /* Safari, Chrome and Opera > 12.1 */
               -moz-animation: fadein 2s; /* Firefox < 16 */
                -ms-animation: fadein 2s; /* Internet Explorer */
                 -o-animation: fadein 2s; /* Opera < 12.1 */
                    animation: fadein 2s;
          }

          @keyframes fadein {
              from { opacity: 0; }
              to   { opacity: 1; }
          }

          /* Firefox < 16 */
          @-moz-keyframes fadein {
              from { opacity: 0; }
              to   { opacity: 1; }
          }

          /* Safari, Chrome and Opera > 12.1 */
          @-webkit-keyframes fadein {
              from { opacity: 0; }
              to   { opacity: 1; }
          }

          /* Internet Explorer */
          @-ms-keyframes fadein {
              from { opacity: 0; }
              to   { opacity: 1; }
          }

          /**
           * Style the subtext
           */
          .slick-text__subtext {
            font-size: 20px;
            font-family: 'Convergence', sans-serif;
            letter-spacing: -1px;
          }

          /**
           * Style the index selectors
           */
          .slick-dots {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
            margin-top: -243px;
            display: flex;
          }

          .slick-dots li button {
            background-color: rgba(255, 255, 255, .5);
            width: 90px;
            height: 5px;
            padding: 0;
            margin-right: 2px;
          }

          .slick-dots li:last-child button {
            margin-right: 0;
          }

          .slick-dots li.slick-active button,
          .slick-dots li:hover button {
            background-color: rgba(255, 255, 255, 1);
          }

          /**
           * Handle smaller screens
           */
          @media (max-width: 1100px) {
            .slick-image {
              height: 360px;
            }

            .slick-text__title {
              font-size: 8rem;
            }
          }
        </style>
        <div class="slick-slide__wrapper">
          <div class="slick-text">
            <h1 class="slick-text__title">${Title}</h1>
            <span class="slick-text__subtext">${Subtext}</span>
          </div>
          <img class="slick-image" src="${Image}" alt="carousel slide ${curEntry_index}">
        </div>
      </div>
    </#list>
  </#if>
</section>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js"></script>
<script>
  $(document).ready(function () {
    function carousel() {
      $('.carousel').slick({
          dots: true,
          infinite: true,
          speed: 1000,
          arrows: false,
          fade: true,
          autoplay: true,
          autoplaySpeed: 7000
      });
    }
    carousel();
  })
</script>
