<template>
  <div id="a">
    <div id="b"></div>
    <div id="c">RESUME</div>
    <div id="d">
      <div id="e">
        <img
          id="f"
          src="https://i.pinimg.com/736x/3b/a2/c4/3ba2c46051c4fc2e7eb353f2eb1f08e4.jpg"
        />
        <h1 style="margin-left: 20px">
          ORLYNZ <br />
          SAMBORA RAHMATULLAH
        </h1>
      </div>
    </div>
    <div class="ab">
      <div class="bb">
        <h2>
          PROFILE
          <hr style="border: 1px dashed black" />
        </h2>
        <div class="cb">
          <p>
            <b>NAME</b><br />
            Orlynz Sambora Rahmatullah
          </p>
          <p>
            <b>DATE OF BIRTH</b><br />
            09 April 2004
          </p>
          <p>
            <b>ADDRESS</b><br />
            Jl. Kalikangkung <br />
            RT2 RW1 <br />
            Semarang <br />
            Indonesia
          </p>
          <h2>
            AWARDS
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>CREATIVE AWARDS 2012</b><br />
            Openminded.org
          </p>
          <p>
            <b>INTERFACE DESIGN 2013</b><br />
            coolideas.com
          </p>
          <h2>
            CONTACT
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>PHONE NUMBER</b><br />
            089 506 616 552
          </p>
          <p>
            <b>EMAIL</b><br />
            orlynzsynthesis90@gmail.com
          </p>
          <h2>
            SOCIAL
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>FACEBOOK</b><br />
            Lynn
          </p>
        </div>
      </div>
      <div class="db">
        <h2>
          GRAPHIC ARTIST
          <hr />
        </h2>
        <div class="eb">
          <h2 style="margin-left: 20px">WORK EXPERIENCE</h2>
          <hr
            style="
              border: 1px dashed black;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 60px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 60px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 60px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px">EDUCATION</h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Project2",
  computed: {
    Project2() {
      return this.$store.state.Project2;
    },
  },
};
</script>
<style>
#a {
  width: 790px;
  padding-bottom: 20px;
  font-family: "Courier New", Courier, monospace;
  background-color: white;
}
#b {
  background-color: darkslateblue;
  height: 40px;
}
#c {
  background-color: darkslateblue;
  height: 2px;
  margin-left: 50px;
  width: 130px;
  font-family: "Courier New", Courier, monospace;
  color: white;
  font-size: 20px;
  text-align: center;
  padding-bottom: 20px;
}
#d {
  background-color: darkslateblue;
  height: 150px;
  font-family: "Courier New", Courier, monospace;
  color: white;
}
#e {
  padding-top: 30px;
  display: flex;
}
#f {
  width: 200px;
  height: 200px;
  display: flex;
  border-radius: 100%;
  margin-left: 20px;
}
.ab {
  display: flex;
}
.bb {
  text-align: right;
  width: 250px;
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 65px;
  padding-bottom: 30px;
}
.cb {
  text-align: right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.db {
  width: 500px;
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 30px;
  padding-bottom: 100px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.eb {
  background-color: rgb(212, 209, 209);
}
.fb {
  background-color: rgb(212, 209, 209);
}
</style>