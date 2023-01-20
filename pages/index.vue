<template>
  <div>
    <div class="section-1">
      <div class="row align-items-top">
        <div class="col-md-7">
          <h1>Build <br> your Business <br> Connections</h1>
          <p class="">Connect with our business architects, build your network and improve lead generation all in one place.</p>
        </div>
        <div class="col-md-5 text-center">
          <img src="~/assets/img/calendar.png" class="img-fluid mb-4" alt="" srcset="">
          <button class="btn btn-prim">Check Availability</button>
        </div>
      </div>
    </div>
    <div class="section-2">
      <div class="row">
        <div class="col-md-5">
          <img src="~/assets/img/graph.png" class="img-fluid" alt="" srcset="">
        </div>
        <!-- <div class="col-1"></div> -->
        <div class="col-md-7">
          <h3>Improved Lead Generation</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien fringilla, mattis ligula consectetur, ultrices mauris. Maecenas vitae mattis tellus..</p>
        </div>
      </div>
    </div>
    <div class="section-3">
      <div class="row">
        <div class="col-md-7">
          <h3 class="text-nowrap">Quality Leads Equal Better ROI</h3>
          <p class="mb-5">Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit urna.</p>
          <ul class="section-3_list">
            <li>Pellentesque sit</li>
            <li>Amet sapien fringilla</li>
            <li>Mattis ligula consectetur</li>
            <li>Ultrices mauris</li>
            <li>Maecenas vitae mattis tellus..</li>
          </ul>
        </div>
        <div class="col-md-5">
          <img src="~/assets/img/Profiles.png" class="img-fluid" alt="" srcset="">
        </div>
      </div>
    </div>
    <div class="section-5">
      <div class="row mb-5">
        <div class="col-12 text-center">
          <h3>Comfortable Plans For You</h3>
        </div>
      </div>
      <div class="row justify-content-evenly align-items-start">
        <div class="col-md-2">
          <div class="card card-1" style="height: 350px">
              <div class="card-body text-center position-relative px-2">
                <h4 style="font-size: 35px; font-weight: 700; padding-top: 60px;">Starter</h4>
                <br>
                <span style="font-size: 30px" class="price">$20</span>
                <div style="height: 55px"></div>
                <div class="text-center">
                  <div class="circle-1 mx-auto text-center " style="bottom: 20px"></div>
                </div>

              </div>
          </div>
        </div>
        <div class="col-md-2">
          <div class="card card-2" style=" width: 210px">
            <div class="card-body text-center px-2">
              <div class="text-center mb-3">
                <div class="circle-2 mx-auto text-center"></div>
              </div>
              <ul class="list-unstyled text-start mb-5">
                <li> <i class="bi bi-check"></i> Emails</li>
                <li> <i class="bi bi-check"></i> CRM</li>
                <li> <i class="bi bi-check"></i> Pool of Lookups</li>
                <li> <i class="bi bi-check"></i> Pool of Lookups</li>
                <li> <i class="bi bi-check"></i> Shared Team Contacts</li>
                <li> <i class="bi bi-check"></i> Salesforce & Zapier Integrations</li>
              </ul>
              <h4 style="font-size: 35px; font-weight: 700;">Pro</h4>
              <span style="font-size: 30px" class="price">$20</span>
              <div style="height: 55px"></div>
            </div>
          </div>
        </div>
        <div class="col-md-2">
          <div class="card card-3" style="height: 350px">
              <div class="card-body text-center position-relative px-2">
                <h4 style="font-size: 35px; font-weight: 700; padding-top: 60px;">Enterprise</h4>
                <br>
                <span style="font-size: 30px" class="price">$30</span>
                <div style="height: 55px"></div>
                <div class="text-center">
                  <div class="circle-3 mx-auto text-center " style="bottom: 20px"></div>
                </div>

              </div>
          </div>
        </div>
      </div>
      <div class="text-center my-5">
        <button class="btn btn-prim">Learn More</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>


<style>
.section-1{
  padding-top: 100px;
  padding-bottom: 150px;
}
.section-2, .section-3{
  padding-bottom: 150px;
}

.section-1 h1{
  padding-bottom: 50px;
}

.section-1 img{
  height: 350px;
}

.section-5 .card{
  border-radius: 200px;
  border: 0;
  background: #FBFBFB;
}

.section-5 .card-1, .card-3{
  box-shadow: 0px 5px 30px rgba(211, 213, 220, 0.3);
}
.section-5 .card-2{
  box-shadow: -12px 4px 60px rgba(211, 213, 220, 0.4), 9px 5px 60px rgba(211, 213, 220, 0.4);
}

.section-5 .card .circle-2{
  width: 80px;
  height: 80px;
  background: linear-gradient(35.94deg, #1DABB4 11.56%, #5CD4DB 58.08%, #A8FEFE 100%);
  box-shadow: inset 27px -4px 20px rgba(52, 124, 129, 0.25);
  border-radius: 50%;
}

.section-5 .card .circle-1, .section-5 .card .circle-3{
  width: 80px;
  height: 80px;
  background: linear-gradient(135deg, #4272EF 0%, rgba(122, 151, 229, 0.7) 100%);
  box-shadow: inset 27px -4px 20px rgba(31, 39, 116, 0.25);
  border-radius: 50%;
}
</style>
