<template>
  <div id="nav" >
    <nav id="navbar-example2" class="navbar navbar-light bg-light px-3">
      <a class="navbar-brand" :href="'/home/'"><h2>Fractalslab</h2></a>
      <ul class="nav nav-pills">
        <li class="nav-item">
          <a id="na" class="nav-link" :href="'/home/'">হোম</a>
        </li>
      </ul>
    </nav>
  </div>

  <div class="container">
    <div class="row">
      <div class="col">
        <h4 class="intro"><strong>ভূমিকা</strong></h4><br>
        <p class="info">যদি আপনি একটি গ্রহণযোগ্য সম্পদ সীমার মধ্যে সম্পূর্ণ বিনামূল্যে আপনার ব্যাকএন্ড REST API চালাতে পারেন? উপরন্তু, আপনাকে চাহিদার উপর ভিত্তি করে সার্ভার পরিচালনা এবং স্থাপন করতে হবে না, যেমন ঈদ বিক্রয়ের সময়। ডেভেলপাররা আজকাল শুধুমাত্র ফিচার ডেভেলপমেন্টে মনোনিবেশ করে, ক্লাউড প্ল্যাটফর্ম যেমন AWS এবং GCP হ্যান্ডলিং সার্ভার ম্যানেজমেন্ট সহ। PaSS এবং SaSS এর মত FaSS (পরিষেবা হিসাবে ফাংশন), সুপরিচিত। এই কোর্সে, আমরা AWS-এ একটি সার্ভারহীন অ্যাপ তৈরি করতে FaSS ব্যবহার করব।</p>
      </div>
      <div class="col">
        <div class="ratio ratio-16x9">
          <iframe class="video" src="https://www.youtube.com/embed/oluY633rkgI" title="YouTube video" allowfullscreen></iframe>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="teacher">
          <div class="card mb-3" style="max-width: 700px;">
            <div class="row g-0">
              <div class="col-md-3">
                <img src="https://scontent.fdac13-1.fna.fbcdn.net/v/t39.30808-1/p320x320/251021110_10218222532894584_942699536956322498_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=7206a8&_nc_ohc=LlB8XxK-BIAAX91k9t2&_nc_ht=scontent.fdac13-1.fna&oh=00_AT85UszNmqrrwzNgeHyWROnSFHfhxw_-XVt5DSRY7sZz9Q&oe=61FE83EF" class="img-thumbnail" alt="...">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h4 class="card-title">শিক্ষক</h4>
                  <h5 class="card-title">সাইফুল ইসলাম</h5>
                  <p id="ch" class="card-text">মোঃ সাইফুল ইসলাম একজন প্রত্যয়িত এডব্লিউএস সমাধান স্থপতি সহযোগী। এডব্লিউএস ক্লাউডে তার ৪+ বছরের অভিজ্ঞতা রয়েছে। এছাড়া তিনি পরামর্শ, সামাজিক কর্মকান্ডের একজন আগ্রহী ভক্ত।</p>
                  <a class="bty" href="https://www.youtube.com/channel/UCDSgZ1hkrD6lKu1dL7AKIfQ"><i class="fab fa-youtube-square"></i></a>
                  <a class="btl" href="https://www.linkedin.com/in/saifulazad/"><i class="fab fa-linkedin"></i></a>
                  <a class="bts" href="https://stackoverflow.com/users/1919324/saiful-azad"><i class="fab fa-stack-overflow"></i></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Button trigger modal -->
      <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
        রেজিস্ট্রেশন
      </button>

      <!-- Modal -->
      <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">রেজিস্ট্রেশন</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
              <div class="form-group">
                <input type="text" class="form-control item" id="username" placeholder="নাম">
              </div>
              <br>
              <div class="form-group">
                <input type="text" class="form-control item" id="email" placeholder="ইমেল">
              </div>
              <br>
              <div class="form-group">
                <input type="text" class="form-control item" id="phone-number" placeholder="ফোন">
              </div>
              <br>
              <div class="form-group">
                <button type="button" class="btn btn-primary">Create Account</button>
              </div>
            </div>
          </div>
        </div>
      </div>
</div>
    <br>
    <div class="row">
      <div class="col">
        <h3><strong>প্রিভিউ কন্টেন্ট</strong></h3><br>
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                সার্ভারহীন
              </button>
            </h2>
            <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li><a href="https://www.youtube.com/watch?v=UxPkK8gW0hs">ভিডিও: সার্ভারহীন কি?</a></li>
                <br>
                <li>সার্ভারলেস স্কেল কি এবং কিভাবে কাজ করে ?</li>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                ল্যাম্বডা
              </button>
            </h2>
            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li><a href="https://www.youtube.com/watch?v=eOBq__h4OJ4">ভিডিও: ল্যাম্বডা কি?</a></li>
                <br>
                <li>ল্যাম্বডা ১০১</li>
                <li>একটি ল্যাম্বডা ফাংশন তৈরি করা হচ্ছে</li>
                <li>ল্যাম্বডা ঘটনা বোঝা</li>
                <li>ল্যাম্বডার লগ প্রবেশ করা হচ্ছে</li>
                <li>পরীক্ষার জন্য একটি টেস্ট পেলোড তৈরি করুন</li>
                <li>এডব্লিউএস কনসোল থেকে একটি ল্যাম্বডা ফাংশন চালান এবং পরীক্ষা করুন</li>
                <li>ল্যাম্বডাকে অনুমতি দেওয়ার জন্য IAM ভূমিকা বরাদ্দ করুন</li>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                এপিআই গেটওয়ে
              </button>
            </h2>
            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li>ল্যাম্বডা ১০১</li>
                <li>কিভাবে একটি রেস্ট এপিআই তৈরি করতে হয়?</li>
                <li>একটি রিসোর্সে এবং এপিআই মেথড তৈরি করা</li>
                <li>একটি এপিআই মেথড এর সাথে ল্যামডা ফাংশান যোগ করা</li>
                <li>ল্যামডা প্রক্সি ইন্টিগ্রেশন</li>
                <li>ল্যামডা CORS এনাবল</li>
                <li>ডেভ স্টেজিং এ API ডেপ্লয় করা</li>
                <li>পোস্টম্যান দ্বারা এপিআই টেস্ট করা</li>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingfour">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsefour" aria-expanded="false" aria-controls="collapsefour">
                ডায়নামোডিবি
              </button>
            </h2>
            <div id="collapsefour" class="accordion-collapse collapse" aria-labelledby="headingfour" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li>ডায়নামোডিবি কি?</li>
                <li>একটি টেবিল তৈরি করুন</li>
                <li>হাতে করে একটি রেকর্ড তৈরি করুন</li>
                <li>বোটো৩ দ্বারা ডায়নামোডিবি-এ ল্যাম্বডা সংযোগ করুন</li>
                <li>ডায়নামোডিবি টেবিলে সিআরইউডি অপারেশন</li>
                <li>পোস্টম্যানের মাধ্যমে এপিআই পরীক্ষা করুন</li>

              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingfive">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsefive" aria-expanded="false" aria-controls="collapsefive">
                মাপকাঠি
              </button>
            </h2>
            <div id="collapsefive" class="accordion-collapse collapse" aria-labelledby="headingfive" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li>এপিআই এ ভার এবং চাপ পরীক্ষা প্রয়োগ করুন</li>
                <li>১০০০টি সমসাময়িক পোস্ট অনুরোধ তৈরি করতে পাইথন স্ক্রিপ্ট তৈরি করুন</li>
                <li>বিভিন্ন পরামিতি পরিবর্তন করুন</li>
                <li>সার্ভারহীন স্কেল অন-ডিমান্ড কিভাবে নিরীক্ষণ করুন</li>
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingsix">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsesix" aria-expanded="false" aria-controls="collapsesix">
                এরপর কি
              </button>
            </h2>
            <div id="collapsesix" class="accordion-collapse collapse" aria-labelledby="headingsix" data-bs-parent="#accordionExample">
              <div class="accordion-body">
                <li>মাইক্রোসার্ভিস ডিজাইন করা</li>
                <li>পর্যবেক্ষণ এবং লগিং</li>
                <li>সার্ভারলেস স্কেল অন-ডিমান্ড কিভাবে পর্যবেক্ষণ করা যায়</li>
              </div>
            </div>
          </div>
        </div>

      </div>
      </div>
  </div>
  <br><br>

<!--  course-->

  <div class="customer-review bg-light">
    <div class="title text-center mb-5">
      <h3 class="font-weight-bolder"><strong>আমাদের কোর্স সম্পর্কে</strong></h3>
    </div>

    <div class="row container px-4">
      <div class="col-lg-4">
        <blockquote class="blockquote text-center">
          <i  class="fa-4x fas fa-user-circle"></i>
        </blockquote>
        <br>
        <blockquote class="blockquote">
          <p class="bl"><strong>Q.কোর্সটি কাদের জন্য ?</strong></p>
          <p class="bl"><i class="fas fa-dot-circle"></i>যাদের AWS পাবলিক ক্লাউড গভীর আগ্রহ রয়েছে</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>যারা বিনামূল্যে API ব্যাকএন্ড তৈরি করতে চায়</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>ব্যাকএন্ড ওয়েব ডেভেলপমেন্ট সম্পর্কে কিছু ধারণা আছে</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>বিভিন্ন AWS সার্টিফিকেশন পরীক্ষা দিতে চান</p>
        </blockquote>
      </div>

      <div class="col-lg-4">
        <blockquote class="blockquote text-center">
          <i  class="fa-4x fas fa-user-circle"></i>
        </blockquote>
        <br>
        <blockquote class="blockquote">
          <p class="bl"><strong>Q. এই কোর্স থেকে আপনি কি শিখবেন?</strong></p>
          <p class="bl"><i class="fas fa-dot-circle"></i>সম্পূর্ণ সার্ভারহীন ব্যাকএন্ড তৈরি করতে পারবেন</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>১০০% বিনামূল্যে REST API ডেভেলপমেন্ট করতে পারবেন</p>
          <p class="bl"><i class="fas fa-dot-circle"></i> প্রধান AWS সার্ভিসে গুলি শিখতে পারবেন</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>বিসার্ভারলেস অ্যাপ্লিকেশনের শক্তি</p>
        </blockquote>
      </div>

      <div class="col-lg-4">
        <blockquote class="blockquote text-center">
          <i  class="fa-4x fas fa-user-circle"></i>
        </blockquote>
        <br>
        <blockquote class="blockquote">
          <p class="bl"><strong>Q. আপনি এই কোর্সের আপনার জ্ঞান কোথায় প্রয়োগ করবেন?</strong></p>
          <p class="bl"><i class="fas fa-dot-circle"></i>এই কোর্সটি AWS জগতে প্রবেশের একটি রাস্তার মতো</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>অনেক কোম্পানি রয়েছে যারা AWS এর বিভিন্ন সার্ভিস নিয়ে কাজ করে তাদের সাথে কাজ করতে পারবেন</p>
          <p class="bl"><i class="fas fa-dot-circle"></i>আপনার জ্ঞান যেকোনো কোম্পানিকে REST API তৈরি করতে সাহায্য করবে।</p>
        </blockquote>
      </div>

  </div>
    <br><br>

    <div class="container px-4">
      <div class="row gx-5">
        <div class="col">
          <blockquote class="blockquote text-center">
            <i  class="fa-4x fas fa-user-circle"></i>
          </blockquote>
          <br>
          <blockquote class="blockquote">
            <p class="bl"><strong>Q. কোর্সের সংস্কৃতি কি?</strong></p>
            <p class="bl"><i class="fas fa-dot-circle"></i>প্রতি সপ্তাহে ২ দিন লাইভ সেশন</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>আপনার কর্মজীবনকে এগিয়ে নেওয়ার জন্য নিজেকে প্রকাশ করার একটি সুযোগ</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>প্রতিটি সেশনে শিক্ষকের সাথে হ্যান্ডস-অন এবং লাইভ কোডিং এর সুযোগ রয়েছে</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>পআপনার শেখার কার্যকারিতা নিশ্চিত করার জন্য রয়েছে অ্যাসাইনমেন্ট।</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>AWS ক্যারিয়ার রিলেটেড কিছু লাইভ সেশন</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>প্রতিটি লেকচারের শেষ প্রশ্ন করে বুঝে নিতে পারবেন</p>
          </blockquote>
        </div>
        <div class="col">
          <blockquote class="blockquote text-center">
            <i  class="fa-4x fas fa-user-circle"></i>
          </blockquote>
          <br>
          <blockquote class="blockquote">
            <p class="bl"><strong>Q. এই কোর্সের পূর্বশর্ত কি ?</strong></p>
            <p class="bl"><i class="fas fa-dot-circle"></i>ব্যাকএন্ডে ওয়েব ডেভেলপমেন্টের কমপক্ষে এক বছরের অভিজ্ঞতা থাকতে হবে</p>
            <p class="bl"><i class="fas fa-dot-circle"></i> ক্রেডিট/ডেবিট/প্রিপেইড কার্ড</p>
            <p class="bl"><i class="fas fa-dot-circle"></i>উচ্চ মানের ইন্টারনেট গতি</p>
          </blockquote>
        </div>
      </div>
    </div>

  </div>
  <br>
<!--          contact-->
  <section class="head pb-5">
    <div class="container py-5">
      <div class="card">
        <div class="card-body">
          <div class="row">
            <div class="col-lg-6 col-md-12 col-sm-12 col-12">
              <div class="row">
                <div class="col-lg-1 offset-1 col-md-2 col-sm-2 col-2">

                </div>
                <div class="col-lg-10 col-md-9 col-sm-9 col-9">
                  <h3 id="con" class="text-center"><strong>আমাদের সাথে যোগাযোগ করুন</strong></h3><br><br>
                  <p>
                    <i class="fas fa-map-marker-alt"></i> মিরপুর, ঢাকা - বাংলাদেশ <br><br>
                    <i class="far fa-envelope"></i> mr.saiful.azad@gmail.com <br><br>
                    <i class="fas fa-phone-alt"></i> ০১৬৭৬৭৪৩০৭৬ <br><br>
                  </p>

                </div>
              </div>
              <br>
              <div class="row">
                <div class="col-lg-1 offset-1 col-md-2 col-sm-2 col-2">

                </div>
                <div class="col-lg-10 col-md-9 col-sm-9 col-9">
                  <p>আমাদের সাথে যোগাযোগ করুন</p>
                  <a class="btl" href="https://www.facebook.com/mr.saiful.azad"><i class="fab fa-facebook-square"></i></a>
                  <a class="btl" href="https://www.linkedin.com/in/saifulazad/"><i class="fab fa-linkedin"></i></a><br><br>
                  <p><i class="fas fa-share"></i> আমাদের ওয়েব শেয়ার করুন:</p>
                  <a class="btl" href="https://www.facebook.com/mr.saiful.azad"><i class="fab fa-facebook"></i></a>
                  <a class="btl" href="https://www.linkedin.com/in/saifulazad/"><i class="fab fa-linkedin"></i></a><br><br>

                </div>
              </div>


            </div>
            <div class="col-lg-6 col-md-12 col-sm-12 col-12 bg-light">
              <form>
                <div class="form-row">
                  <div class="form-group col-lg-6 col-md-12 col-sm-12 col-12">
                    <label><h2><strong>রেজিস্ট্রেশন</strong></h2></label><br><br>
                    <input type="text" class="form-control" placeholder="নাম"><br>
                    <input type="email" class="form-control" placeholder="ইমেল"><br>
                    <input type="phone" class="form-control" placeholder="ফোন"><br><br>
                    <label><input type="checkbox">  I'm not a robort</label><br><br>
                    <button class="bu">রেজিস্ট্রেশন করুন</button>
                  </div>
                </div>
              </form>

            </div>


          </div>

        </div>

      </div>
    </div>

  </section>
</template>

<script lang="ts">
import { Vue } from 'vue-class-component';

export default class Home extends Vue {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
body{
  overflow-x: hidden;
}
#na{
  color: dodgerblue;
  padding: 0px 400px 0px 0px;
  font-size: 18px;
  margin-left: 102px;
}
.navbar-brand,h2{
  color: dodgerblue;
  padding: 8px;
}
h4.intro{
  padding: 30px 0px 0px 0px;
  font-size: 25px;
}
p.info {
  font-family: jost, sans-serif;
  line-height: 2rem;
  font-size: 16px;
  text-align: justify;
}
#ch{
  font-family: jost, sans-serif;
  line-height: 2rem;
  font-size: 16px;
  text-align: justify;
}

a.bty{
  color: red;
  font-size: 25px;
  padding: 0px 10px 0px 0px;
}
a.btl{
  color: dodgerblue;
  font-size: 25px;
  padding: 0px 10px 0px 0px;
}
a.bts{
  color: dodgerblue;
  font-size: 25px;
}
.video{
  padding: 30px 0px 0px 80px;
}
.bl{
  color: black;
  text-align: justify;
  padding: 0px 0px 0px 40px;
}
p.bl{
  font-size: 16px;
}
#con{
  color: dodgerblue;
}
.bu{
  background-color: dodgerblue;
  color: #fff;
}
</style>

