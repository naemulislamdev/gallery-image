setp: 1
 <link rel="stylesheet" href="dist/simple-lightbox.css" />
 <style>
      .img-box {
        box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
        padding: 7px 7px;
        height: 200px;
      }
      .img-box > a > img {
        width: 100%;
        height: 100%;
      }
    </style>
 step: 2
 <div class="row">
          <div class="col-md-12">
            <div class="gallery">
              <div class="row">
                <div class="col-md-3 mb-3">
                  <div class="img-box">
                    <a href="img/img1.jpg" class="big">
                      <img src="img/img1.jpg" alt="" title="Beautiful Image" />
                    </a>
                  </div>
                </div>
                <div class="col-md-3 mb-3">
                  <div class="img-box">
                    <a href="img/img2.jpg"
                      ><img src="img/img2.jpg" alt="" title=""
                    /></a>
                  </div>
                </div>
              </div>
              <div class="clear"></div>
            </div>
          </div>
        </div>
step: 3
<script src="dist/simple-lightbox.js"></script>
    <script>
      (function () {
        var $gallery = new SimpleLightbox(".gallery a", {});
      })();
    </script>
