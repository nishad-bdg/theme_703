<template>
  <div class="hold_theme_703">
    <b-container fluid class="header">
      <b-row>
        <b-col md="5">
          <div class="hold_profile">
            <div class="profile_picture">
              <img class="circle" src="@/assets/img/profile_pic.jpg" alt="Profile Picture" />
            </div>
            <div class="profile_info">
              <h2 class="name">Wilkerson Doe</h2>
              <p class="designation">Web Developer & UX Designer</p>
              <div class="contact_media">
                <div class="direct_contact">
                  <a href="#">
                    <img src="../assets/img/chatbubbles.svg" alt="Chat" />
                    <p>chat</p>
                  </a>
                </div>
                <div class="direct_contact">
                  <a href="#">
                    <img src="../assets/img/audio.svg" alt="Audio" />
                    <p>Audio</p>
                  </a>
                </div>
                <div class="direct_contact">
                  <a href="#">
                    <img src="../assets/img/videocam.svg" alt="video" />
                    <p>Video</p>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </b-col>
        <b-col md="5" sm="12" cols="12">
          <div class="price_rate">
            <div class="hold_bg">
              <div class="availability">
                <span>
                  <p>$50</p>usd
                </span>
                <p>Hourly Rate</p>
              </div>

              <div class="availability">
                <span>
                  <p>15</p>Hours
                </span>
                <p>Weekly Availability</p>
              </div>
            </div>
          </div>
        </b-col>
        <b-col md="2">
          <div class="connect_social_media">
            <div class="social_icon_link">
              <a href="#">
                <img src="../assets/img/linkedin.svg" alt="Linked In" />
              </a>
              <a href="#">
                <img src="../assets/img/dribble.svg" alt="Dribble" />
              </a>
              <a href="#">
                <img src="../assets/img/twitter.svg" alt="Twitter" />
              </a>
              <a href="#">
                <img src="../assets/img/facebook.svg" alt="facebook" />
              </a>
            </div>

            <b-button class="hire_me">Hire me!</b-button>
          </div>
        </b-col>
      </b-row>
    </b-container>

    <div class="navigation">
      <b-tabs v-model="tabIndex" content-class="mt-3" fill nav-class="nav-tab-703">
        <b-tab class="addHere" :title-link-class="[linkClass(0), 'tab_703' ]">
          <template v-slot:title>
            <img src="../assets/img/portfolio.svg" alt />
            <p>Portfolio</p>
          </template>
          <div class="tab-content-wrapper">
            <b-row>
              <b-col lg="6" md="6" xl="5">
                <div class="left_content">
                  <h2 class="p-title">
                    WEBSITE
                    USER INTERFACE
                  </h2>
                  <p
                    class="p_details"
                  >Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam eirmod tempor dolore.</p>

                  <div class="slider_btn">
                    <div class="prev_btn">
                      <img src="@/assets/img/prev_btn.svg" alt />
                    </div>
                    <div class="next_btn">
                      <img src="../assets/img/next_btn.svg" alt />
                    </div>
                  </div>
                </div>
              </b-col>
              <b-col lg="6" md="6" xl="7" class="slider_image">
                <b-row>
                  <b-col cols="6" sm="6" md="12" xl="6" class="portfolio_img pb-4">
                    <img src="../assets/img/p_img_one.png" alt />
                  </b-col>
                  <b-col cols="6" sm="6" md="12" xl="6" class="portfolio_img pb-4">
                    <img src="../assets/img/p_img_one.png" alt />
                  </b-col>
                  <b-col cols="6" sm="6" md="12" xl="6" class="portfolio_img pb-4">
                    <img src="../assets/img/p_img_one.png" alt />
                  </b-col>
                  <b-col cols="6" sm="6" md="12" xl="6" class="portfolio_img pb-4">
                    <img src="../assets/img/p_img_one.png" alt />
                  </b-col>
                </b-row>

                <!-- <img src="../assets/img/p_img_two.jpg" alt />
                <img src="../assets/img/p_img_one.png" alt />
                <img src="../assets/img/p_img_two.jpg" alt />-->
              </b-col>
            </b-row>
          </div>
        </b-tab>
        <b-tab :title-link-class="[linkClass(1),'tab_703']">
          <template v-slot:title>
            <img src="../assets/img/experience.svg" alt />
            <p>Experience</p>
          </template>

          <div class="tab-content-wrapper">
            <b-row>
              <b-col md="5" offset-md="1" class="card_item-703">
                <div class="exp_card">
                  <div class="title">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon.svg" alt />
                    </div>
                    <h3>Ui Designer</h3>
                  </div>

                  <div class="experience_details">
                    <p class="date">26th October,2019</p>
                    <div class="company-name">
                      <img src="@/assets/img/location_icon.svg" alt />
                      <p>Example IT Limited, Dhaka</p>
                    </div>
                    <p
                      class="details"
                    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur sequi totam dolorem deserunt, alias aspernatur minima dicta officiis reprehenderit, deleniti, commodi eveniet porro impedit facere sed aliquam officia repudiandae id.</p>
                  </div>
                </div>
              </b-col>
              <b-col md="5" offset-md="1" class="card_item-703">
                <div class="exp_card">
                  <div class="title">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon.svg" alt />
                    </div>
                    <h3>Ui Designer</h3>
                  </div>

                  <div class="experience_details">
                    <p class="date">26th October,2019</p>
                    <div class="company-name">
                      <img src="@/assets/img/location_icon.svg" alt />
                      <p>Example IT Limited, Dhaka</p>
                    </div>
                    <p
                      class="details"
                    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur sequi totam dolorem deserunt, alias aspernatur minima dicta officiis reprehenderit, deleniti, commodi eveniet porro impedit facere sed aliquam officia repudiandae id.</p>
                  </div>
                </div>
              </b-col>
            </b-row>
          </div>
        </b-tab>
        <b-tab :title-link-class="[linkClass(2), 'tab_703']">
          <template v-slot:title>
            <img src="../assets/img/skills.svg" alt />
            <p>Skills</p>
          </template>
          <div class="tab-content-wrapper">
            <b-row v-if="!show">
              <b-col md="5" class="mx-auto">
                <b-list-group>
                  <b-list-group-item class="skill_tab" href="#some-link" @click="show=!show">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>UI Design</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                  <b-list-group-item class="skill_tab" href="#">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>App Development</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                  <b-list-group-item class="skill_tab" href="#">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>Back-End</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                </b-list-group>
              </b-col>
              <b-col md="5" class="mx-auto">
                <b-list-group>
                  <b-list-group-item class="skill_tab" href="#some-link">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>UI Design</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                  <b-list-group-item class="skill_tab" href="#">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>App Development</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                  <b-list-group-item class="skill_tab" href="#">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon_color.svg" alt />
                    </div>
                    <h3>Back-End</h3>
                    <b-icon class="right_icon" icon="chevron-right"></b-icon>
                  </b-list-group-item>
                </b-list-group>
              </b-col>
            </b-row>

            <b-row v-if="show">
              <b-col md="5" offset-md="1" offset-sm="0" class="card_item-703">
                <div class="exp_card skill_card">
                  <div class="title">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon.svg" alt />
                    </div>
                    <h3>Ui Designer</h3>
                  </div>

                  <div class="experience_details skills_details">
                    <p
                      class="details"
                    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur sequi totam dolorem deserunt, alias aspernatur minima dicta officiis reprehenderit, deleniti, commodi eveniet porro impedit facere sed aliquam officia repudiandae id.</p>
                    <b-button class="btn close_btn" @click="show=!show">Close</b-button>
                  </div>
                </div>
              </b-col>
              <b-col md="5" offset-md="1" offset-sm="0" class="card_item-703" align-self="end">
                <div class="margin_bottom" v-for="(bar,index) in bars" :key="index">
                  <div class="progress_label">
                    <p>{{bar.label}}</p>
                    <p>{{bar.value}}%</p>
                  </div>
                  <b-progress :max="max" :key="bar.variant" class="bg_progress">
                    <b-progress-bar :value="bar.value" :style="{backgroundColor:bar.variant}"></b-progress-bar>
                  </b-progress>
                </div>
              </b-col>
            </b-row>
          </div>
        </b-tab>
        <b-tab :title-link-class="[linkClass(3),'tab_703']">
          <template v-slot:title>
            <img src="../assets/img/education.svg" alt />
            <p>Education</p>
          </template>
          <div class="tab-content-wrapper">
            <b-row>
              <b-col md="5" offset-md="1" offset-sm="0" class="card_item-703">
                <div class="exp_card">
                  <div class="title">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon.svg" alt />
                    </div>
                    <h3>Ui Designer</h3>
                  </div>

                  <div class="experience_details">
                    <p class="date">26th October,2019</p>
                    <div class="company-name">
                      <img src="@/assets/img/location_icon.svg" alt />
                      <p>Example IT Limited, Dhaka</p>
                    </div>
                    <p
                      class="details"
                    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur sequi totam dolorem deserunt, alias aspernatur minima dicta officiis reprehenderit, deleniti, commodi eveniet porro impedit facere sed aliquam officia repudiandae id.</p>
                  </div>
                </div>
              </b-col>
              <b-col md="5" offset-md="1" offset-sm="0" class="card_item-703">
                <div class="exp_card">
                  <div class="title">
                    <div class="circle_icon">
                      <img src="../assets/img/exp_icon.svg" alt />
                    </div>
                    <h3>Ui Designer</h3>
                  </div>

                  <div class="experience_details">
                    <p class="date">26th October,2019</p>
                    <div class="company-name">
                      <img src="@/assets/img/location_icon.svg" alt />
                      <p>Example IT Limited, Dhaka</p>
                    </div>
                    <p
                      class="details"
                    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur sequi totam dolorem deserunt, alias aspernatur minima dicta officiis reprehenderit, deleniti, commodi eveniet porro impedit facere sed aliquam officia repudiandae id.</p>
                  </div>
                </div>
              </b-col>
            </b-row>
          </div>
        </b-tab>

        <b-tab :title-link-class="[linkClass(4),'tab_703']">
          <template v-slot:title>
            <img src="../assets/img/about.svg" alt />
            <p>About</p>
          </template>
          <div class="tab-content-wrapper">
            <b-row>
              <b-col md="7" class="text-right sm-text-left">
                <div class="about_person">
                  <h3 class="person_name">Wilkerson Doe</h3>
                  <p>
                    I'm Creative Director and UI/UX Designer from New York, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.
                    My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add a personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way.
                  </p>
                </div>

                <div class="about_person_mobile">
                  <h3 class="person_name">Wilkerson Doe</h3>
                  <p>I'm Creative Director and UI/UX Designer from New York, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.</p>
                  <p>My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add a personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way.</p>
                </div>

                <div class="person_info">
                  <div class="info">
                    <p>Dhaka, Bangladesh</p>
                    <img src="../assets/img/id_icon.svg" alt />
                  </div>

                  <div class="info">
                    <p>example@123.com</p>
                    <img src="../assets/img/email.svg" alt />
                  </div>

                  <div class="info">
                    <p>+1234567890</p>
                    <img src="../assets/img/audio.svg" alt />
                  </div>
                  <b-button size="lg" class="hire_me view_resume">View Resume</b-button>
                </div>
              </b-col>

              <b-col md="4" offset-md="1" class="person_image">
                <img src="../assets/img/person_picture.jpg" alt />
              </b-col>

              <b-col cols="12" sm="12" class="person_image_mobile">
                <div class="person_info_mobile">
                  <div class="info">
                    <p>Dhaka, Bangladesh</p>
                    <img src="../assets/img/id_icon.svg" alt />
                  </div>

                  <div class="info">
                    <p>example@123.com</p>
                    <img src="../assets/img/email.svg" alt />
                  </div>

                  <div class="info">
                    <p>+1234567890</p>
                    <img src="../assets/img/audio.svg" alt />
                  </div>
                  <b-button size="lg" class="hire_me view_resume">View Resume</b-button>
                </div>

                <div class="single_image">
                  <img src="../assets/img/person_picture.jpg" alt />
                </div>
              </b-col>
            </b-row>
          </div>
        </b-tab>
      </b-tabs>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Theme703',
  data() {
    return {
      tabIndex: 0,
      show: false,
      bars: [
        { variant: '#FF4900', value: 75, label: 'Html', max: 100 },
        { variant: '#FF8800', value: 36, label: 'CSS', max: 100 },
        { variant: '#FFC400', value: 25, label: 'bootstrap', max: 100 },
        { variant: '#FF8800', value: 80, label: 'javascript', max: 100 }
      ]
    };
  },
  methods: {
    linkClass(idx) {
      if (this.tabIndex === idx) {
        return ['active-tab-703'];
      } else {
        return ['text-light'];
      }
    }
  }
};
</script>

<style lang='scss' scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;300;400&family=Playfair+Display:wght@700&display=swap');

$body-bg-color: #000;
$primary-color: #ff4900;
$title-font-one: 'Playfair Display', serif;
$secondary-font: 'Montserrat', sans-serif;
$sfui-font: 'SFUIText', sans-serif;
* {
  box-sizing: border-box;
}
a {
  text-decoration: none;
  &:hover {
    text-decoration: none;
  }
}

h1,
h2,
h3,
h4,
h5,
h6,
p,
span {
  margin: 0;
  padding: 0;
}
.hold_theme_703 {
  width: 100%;
  height: 100vh;
  background: $body-bg-color;
  color: #fff;
  overflow-x: hidden;
}

.header {
  min-height: 245px;
  width: 95%;
  margin: 0 auto;
  position: relative;
}

.hold_profile {
  min-height: 210px;
  position: relative;

  @media (max-width: 767.98px) {
    min-height: auto;
    flex-direction: column;
    align-items: center;
  }

  &:before {
    position: absolute;
    top: 0;
    left: -63px;
    height: 245px;
    width: 111px;
    background: #ff4900;
    z-index: 1;
    content: '';

    @media (max-width: 767.98px) {
      left: -24px;
      height: 111px;
      width: 100vw;
    }
  }
}

.hold_profile,
.price_rate,
.contact_media {
  display: flex;
  align-items: center;
}

.profile_picture {
  position: relative;
  z-index: 5;
  @media (max-width: 767.98px) {
    margin-top: 55px;
    margin-bottom: 25px;
  }
  img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  &::before {
    position: absolute;
    content: '';
    top: -50%;
    left: -50%;
    width: 120px;
    height: 120px;
    background: transparent;
    border-radius: 50%;
    border: 5px solid #fff;
    transform: translate(33%, 33.5%);
  }

  &::after {
    position: absolute;
    content: '';
    top: -50%;
    left: -50%;
    width: 110px;
    height: 110px;
    background: transparent;
    border-radius: 50%;
    border: 5px solid #ff4900;
    transform: translate(41%, 41%);
  }
}

.profile_info {
  width: 100%;
  margin-left: 25px;

  @media (max-width: 767.98px) {
    margin-left: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .name {
    font-family: $title-font-one;
    font-weight: 700;
    font-size: calc(1.7vw + 20px);
    text-transform: capitalize;
    margin-bottom: 0;
  }
  .designation {
    font-family: $secondary-font;
    font-weight: 400;
    margin-top: 10px;
    margin-bottom: 37px;
  }

  .direct_contact {
    margin-right: 40px;
    &:last-child {
      margin-right: 0;
    }
    a {
      display: flex;
      flex-direction: column;
      align-items: center;
      img {
        width: 24px;
        height: 22px;
        margin-bottom: 5px;
      }

      p {
        color: #fff;
        text-decoration: none;
        text-transform: capitalize;
        font-family: $secondary-font;
        font-weight: 400;
      }
    }
  }
}

.price_rate {
  min-height: 200px;
  display: flex;
  align-items: flex-start;
  @media (max-width: 767.98px) {
    align-items: center;
    min-height: auto;
  }
  .hold_bg {
    background: $primary-color;
    width: 70%;
    display: flex;
    justify-content: space-around;
    min-height: 138px;
    align-items: center;
    @media (max-width: 767.98px) {
      width: 100%;
      background: transparent;
    }
    .availability {
      @media (max-width: 767.98px) {
        display: flex;
        align-items: center;
        justify-content: center;
      }
      span {
        font-family: $title-font-one;
        font-weight: 700;
        font-size: 1.3rem;
        display: inline-block;
        @media (max-width: 767.98px) {
          display: flex;
          align-items: center;
          justify-content: center;
          font-size: 14px;
          color: $primary-color;
        }

        p {
          font-size: 2rem;
          display: inline-block;
          font-family: $title-font-one;
          margin-right: 5px;
          text-transform: uppercase;

          @media (max-width: 767.98px) {
            font-size: 14px;
            color: $primary-color;
          }
        }
      }
      > p {
        font-family: $secondary-font;
        font-weight: 300;
        opacity: 0.5;

        @media (max-width: 767.98px) {
          font-size: 12px;
          order: -1;
          opacity: 1;
          margin-top: 2px;
          margin-right: 10px;
        }
      }
    }
  }
}

.connect_social_media {
  min-height: 210px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  @media (max-width: 767.98px) {
    display: none;
  }
}

.social_icon_link {
  display: flex;
  justify-content: space-between;
  margin-bottom: 3.5rem;

  a {
    height: 20px;
    display: inline-block;
    margin-right: 25px;
    &:last-child {
      margin-right: 0;
    }
    img {
      height: 100%;
    }
  }
}

.hire_me {
  background: $primary-color;
  transition: all 0.5s ease-in-out;
  font-family: $secondary-font;
  border: none;
  padding: 0.7rem 0rem;
  &:hover {
    background: lighten($color: $primary-color, $amount: 30);
    color: #000;
  }
}

.tab_703 {
  p {
    text-transform: capitalize;
    font-family: $secondary-font;
    font-family: 400;
    font-size: 20px;
    @media (max-width: 767.98px) {
      font-size: 16px;
    }
  }
}

.tab-content-wrapper {
  width: 90%;
  margin: 0 auto;
  padding-bottom: 2rem;
  padding-top: 2rem;
}

.portfolio_img {
  img {
    width: 100%;
  }
}

.slider_image {
  @media (max-width: 767.98px) {
    margin-top: 4rem;
  }
}

.left_content {
  padding-right: 10rem;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 100%;
  position: relative;
  @media (max-width: 768px) {
    padding-right: 0;
  }
  &:before {
    width: 5px;
    height: 100%;
    position: absolute;
    top: 0;
    right: 59px;
    background: $primary-color;
    content: '';

    @media (max-width: 768px) {
      display: none;
    }
  }

  .p-title {
    font-size: 3rem;
    position: relative;

    @media (max-width: 767.98px) {
      font-size: 14px;
      text-align: center;
    }

    @media (min-width: 768px) and (max-width: 1024px) {
      font-size: 2rem;
    }
    &:before {
      position: absolute;
      bottom: -20px;
      left: 0px;
      width: 100px;
      height: 5px;
      background: $primary-color;
      content: '';

      @media (max-width: 767.98px) {
        display: none;
      }
    }
  }
}

.p_details {
  margin: 2rem 0;
  @media (max-width: 767.98px) {
    display: none;
  }
}

.slider_btn {
  display: flex;
  justify-content: space-between;
  align-items: center;

  @media (max-width: 767.98px) {
    position: absolute;
    width: 100%;
  }

  .prev_btn,
  .next_btn {
    cursor: pointer;
    width: 50px;
    height: 50px;
    border: 1px solid #fff;
    padding: 15px;
    display: flex;

    img {
      width: 100%;
    }
  }
}

.card_item_703 {
  position: relative;
}

.exp_card {
  color: #000;
  background: #fff;
  padding: 2rem;
  position: relative;
  margin-bottom: 20px;
  &:before {
    position: absolute;
    top: 0px;
    left: 0;
    width: 62px;
    height: 103px;
    background: $primary-color;
    content: '';
    z-index: 0;
  }
  &:after {
    position: absolute;
    top: 103px;
    left: 0;
    width: 100%;
    height: 5px;
    background: $primary-color;
    content: '';
  }

  .circle_icon {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: $primary-color;
    display: flex;
    justify-content: center;
    img {
      width: 25px;
      position: relative;
      z-index: 2;
    }
  }
  .title {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 2rem;
    h3 {
      text-transform: uppercase;
      color: $primary-color;
      font-size: 1.8rem;
      font-weight: bold;

      @media (max-width: 767.98px) {
        font-size: 1rem;
        flex-basis: 65%;
      }
    }
  }
}

.experience_details {
  .date {
    font-size: 1.2rem;
    font-weight: bold;
    text-transform: capitalize;
    margin-bottom: 12px;
  }

  .company-name {
    display: flex;
    img {
      margin-right: 10px;
      width: 20px;
    }

    p {
      font-size: 15px;
      font-weight: bold;
      text-transform: capitalize;
      color: #000;
      margin-bottom: 12px;
    }
  }

  .details {
    margin-top: 15px;
    color: #202020;
    line-height: 28px;
  }
}

.skill_tab {
  display: flex;
  background: #111111;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 2.2rem;
  transition: all 0.3s ease-in-out;
  outline: none;
  &:focus {
    background: #111111;
  }
  &:hover {
    background: $primary-color;
    transition: background 0.3s ease-in-out;
    .circle_icon {
      background: #fff;
      transition: background 0.3s ease-in-out;
    }

    .right_icon {
      color: #fff;
      transition: color 0.3s ease-in-out;
    }
  }

  .circle_icon {
    width: 70px;
    height: 70px;
    border-radius: 50%;
    background: #000;
    display: flex;
    justify-content: center;

    img {
      width: 30px;
    }
  }

  h3 {
    flex-basis: 50%;
    text-transform: uppercase;
    font-size: 17px;
    color: #fff;
  }
}

.skills_details {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.right_icon {
  font-size: 28px;
  font-weight: bold;
  color: $primary-color;
}

.about_person_mobile {
  padding-bottom: 2rem;
  border-bottom: 5px solid $primary-color;
  margin-bottom: 2rem;
  @media (min-width: 767.98px) {
    display: none;
  }

  .person_name {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    font-family: $secondary-font;
    color: $primary-color;
  }

  > p {
    font-family: $secondary-font;
    font-size: 15px;
    line-height: 28px;
    color: #fff;
    margin-bottom: 15px;
  }
}

.about_person {
  padding-bottom: 2rem;
  border-bottom: 5px solid $primary-color;
  margin-bottom: 2rem;
  display: none;

  @media (min-width: 768px) {
    display: block;
  }

  .person_name {
    font-size: 3rem;
    margin-bottom: 2rem;
    font-family: $secondary-font;
    color: $primary-color;
  }
  > p {
    font-family: $secondary-font;
    font-size: 15px;
    line-height: 28px;
    color: #fff;
  }
}

.person_image_mobile {
  display: flex;
  .single_image {
    width: 30%;
    margin-left: 20px;

    img {
      width: 100%;
      border-radius: 15px;
    }
  }
  @media (min-width: 767.98px) {
    display: none;
  }
}

.person_image {
  width: 60%;
  @media (max-width: 768px) {
    display: none;
  }

  img {
    width: 100%;
    border-radius: 15px;
  }
}

.person_info_mobile {
  width: 70%;
  text-align: right;
  @media (min-width: 767.98px) {
    display: none;
  }

  .view_resume {
    margin-top: 10px;
    padding: 0.5rem 0.8rem;
    outline: none;
    font-size: 15px;
  }

  .info {
    > p {
      font-size: 14px;
    }
  }
}

.person_info {
  display: none;
  @media (min-width: 768px) {
    display: block;
  }
}

.info {
  display: flex;
  justify-content: flex-end;
  margin-bottom: 15px;

  > p {
    margin-right: 15px;
    font-family: $secondary-font;
    font-size: 16px;
    text-transform: capitalize;
  }

  img {
    width: 20px;
  }
}

.view_resume {
  margin-top: 20px;
  padding: 1rem 2rem;
  outline: none;
  &:focus {
    background: $primary-color;
  }
}

.sm-text-left {
  @media (max-width: 767.98px) {
    text-align: left !important;
  }
}

.close_btn {
  padding: 0.6rem 2rem !important;
  margin-top: 15px;
  text-transform: uppercase;
  background: $primary-color;
  outline: none;
  border: none;
  &:focus {
    background: $primary-color;
  }
}

.progress_label {
  display: flex;
  justify-content: space-between;
  text-transform: uppercase;
  font-size: 15px;
}

.bg_progress {
  height: 0.8rem;
  border-radius: 30px;
  background-color: #858585;
}

.margin_bottom {
  margin-bottom: 2rem;
  &:last-child {
    margin-bottom: 0;
  }
}

.skill_card {
  margin-bottom: 0;

  @media (max-width: 767.98px) {
    margin-bottom: 20px;
  }
}
</style>