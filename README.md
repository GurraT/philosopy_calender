# philosopy_calender

  
          <div class="day1">
              
              <button type="button" class="btn btn-outline-light" id="toast1">.1.</button>

              <div class="toast bg-dark" data-autohide="false">
                <div class="toast-header">
                  Renaissance masters Raffaello Sanzio da Urbino 
                  <img src="assets/img/rapheal.jpg" height="10%" width="10%" class="rounded me-2" alt="raphael">
                  <button type="button" class="btn-close ml-2 mb-1" data-dismiss="toast" aria-label="Close"> x </button>                </div>
                <div class="toast-body">
                  His frescoe School of Athen was painted around the years 1509 and is still to be seen in Vatican.
                </div>
              </div>
            </div>

            <div class="day2">
              
              <button type="button" class="btn btn-outline-light" id="toast2">.2.</button>

              <div class="toast bg-dark" data-autohide="false">
                <div class="toast-header">
                  Appollo the Good of truth, music and poetry 
                  <img src="assets/img/appollo.jpg" height="20%" width="20%" class="rounded me-2" alt="appollo">
                  <button type="button" class="btn-close ml-2 mb-1" data-dismiss="toast" aria-label="Close"> x </button>                </div>
                <div class="toast-body">
                  Important dives connected to Appollo was <br> "Be truth to yourself" and <br> "Always be moderate"
                </div>
              </div>
            </div>

         </div>
         </div>

         

       
       <script>
 
       $(document).ready(function(){
         $("#toast1").click(function(){
           $('.toast').toast('show');
         });
       });
       </script>