# FewLines Isotipo en CSS

juguando con css arme el isotipo de mi empresa

<svg fill="none" viewBox="0 0 120 120" width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
        <style>
            .FL{
              width: 30px;
              height: 69px;
            }
            .F {
                position: relative;
                width: 100%;
                height: 100%;
                border-width: 21px 0 0 21px;
                border-style: solid;
                border-color: #3f51b5;
            }
            .F::before {
                content: "";
                position: absolute;
                width: 18px;
                height: 21px;
                left: 0;
                top: 21px;
                background: #3f51b5;
            }
            .F1:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: white;
                position: absolute;
                top: -55%;
                left: -126.66%;
                transform: rotate(45deg);
            }
            .F2:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: #3f51b5;
                position: absolute;
                top: 54px;
                left: -36px;
                transform: rotate(45deg);
            }
            .F3:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: #3f51b5;
                position: absolute;
                top: -36px;
                left: 15px;
                transform: rotate(45deg);
            }
            
            .L {
                left:98%;
                top:-98%;
                position: relative;
                width: 100%;
                height: 100%;
                border-style: solid;
                border-color: #3f51b5;
                border-width: 0 21px 21px 0;
            }
            
            .L::after {
                content: "";
                position: absolute;
                bottom: 0;
                right: left;
                width: 21px;
                height: 0px;
                background: #3f51b5;
            }
            .L1:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: white;
                position: absolute;
                top: 77px;
                left: 39px;
                transform: rotate(-135deg);
            }
            .L2:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: #3f51b5;
                position: absolute;
                top: 75px;
                left: -15px;
                transform: rotate(-135deg);
            }
            .L3:after {
                content: '';
                display: block;
                width: 0;
                height: 0;
                border: 15px solid transparent;
                border-right-color: #3f51b5;
                position: absolute;
                top: -15px;
                left: 36px;
                transform: rotate(-135deg);
            }
        </style>
        <div class="FL">
            <div class="F">
              <div class="F1"></div>
              <div class="F2"></div>
              <div class="F3"></div>
            </div>
            <div class="L">
              <div class="L1"></div>
              <div class="L2"></div>
              <div class="L3"></div>
            </div>
        </div>
      </foreignObject>
</svg>
