<template>
    <div>
        <Navbar />

        <section class="about">

            <h1 class="heading"> about <span>me</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>personal info</h1>

                    <div class="box-container">

                        <div class="box">
                            <h3> <span>name : </span> Panusbodee Pisutsuwimon </h3>
                            <h3> <span>age : </span> 19 </h3>
                            <h3> <span>email : </span> panusbodee.pisu@bumail.net </h3>
                            <h3> <span>address : </span> Phathum, Thailand 12110 </h3>
                        </div>

                        <div class="box">
                            <h3> <span>Study : </span> available </h3>
                            <h3> <span>skill : </span> Song Editor </h3>
                            <h3> <span>experience : </span> 1 years </h3>
                            <h3> <span>language : </span> thai,english </h3>
                        </div>

                    </div>

                    <a href="/profilewithcss/files/resume.pdf" class="btn"> download my pruduct <i class="fas fa-download"></i>
                    </a>

                </div>

                <div class="count-container">

                    <div class="box">
                        <h3>1+</h3>
                        <p>years of Learning</p>
                    </div>

                    <div class="box">
                        <h3>10+</h3>
                        <p>happy feelings</p>
                    </div>

                    <div class="box">
                        <h3>17+</h3>
                        <p>project completed</p>
                    </div>

                    <div class="box">
                        <h3>2+</h3>
                        <p>Certificates</p>
                    </div>

                </div>

            </div>

        </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

        <section class="skills">

            <h1 class="heading"> <span>my</span> skills </h1>

            <div class="box-container">
                <div class="box">
                    <img src="images/icon-1.png">
                    <h3>html</h3>
                </div>
                <div class="box">
                    <img src="images/icon-2.png">
                    <h3>css</h3>
                </div>
                <div class="box">
                    <img src="images/icon-3.png">
                    <h3>javascript</h3>
                </div>
                <div class="box">
                    <img src="images/icon-4.png">
                    <h3>sass</h3>
                </div>
                <div class="box">
                    <img src="images/icon-5.png">
                    <h3>angular</h3>
                </div>
                <div class="box">
                    <img src="images/icon-6.png">
                    <h3>react.js</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

        <!-- education section starts  -->

        <section class="education">

            <h1 class="heading"> <span>my</span> experience </h1>

            <div class="box-container">

                <div class="box">
                    <i class="fas fa-briefcase"></i>
                    <span>2021-2022</span>
                    <h3>Learning in Bangkok University</h3>
                    <p>I decion to above myself and find something new in my life and learning anything I don't know</p>
                </div>

            </div>

        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import axios from axios

export default{
    components: { Navbar },
    methods:    {
        async fetchExprience() {
            try {
                let res = await axios.get( https//633fc566e44b83bc73c0f545.mockapi.io/profile/v1/experiences )
                this.experiences = res.data

            } catch (error) {

            }
        }
    },
    data() {
        return{
            experiences:[]
        }
    },
        async fetchskills() {
                try {
                    let res = await axios.get( https://633fc566e44b83bc73c0f545.mockapi.io/profile/v1/skills )
                    this.skills = res.data

                }, trycatch (error) {

                }
            }
        }
        data() {
            return{
                experiences:[]
            }
        }
        beforeMount()   {;
            this.fetchskills
        }

   

for (let index = 0; index < array.length; index++) {
	const element = array[index];
	}
do {
	}
} while (condition);,
</script>

<style>

</style>