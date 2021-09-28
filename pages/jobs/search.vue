<template>
  <div class="con">
      <div class="all">
        <h3>Find the Perfect Job
</h3>
        <p>Only a select few mandates being handled by us are posted on our website and other online platforms. A vast majority of jobs aren’t in the public domain. Be a part of our searchable centralized database by sending us your details.</p>
        <div class="view"></div>
      </div>
      <div class="info">
          <h5>
            Mid and Senior level Professionals
          </h5>
      <p>
          If you are an experienced leader in the bracket of 5-10 or over 10+ years of experience
seeking a new opportunity, or seeking support in career transition, please feel free to submit
your resume to – <a>solutionsbizzcon@gmail.com</a>
      </p>
      <br>
      <p>
        Many senior professionals today seek support of an executive coach to craft career strategy
to support them in their development plans and manage change.
      </p>
     <br>
     <p>
       You may also wish to visit our website in detail to learn about our personalized Career
Coaching & transition services. Our range of services includes Leadership Development,
career planning, On-boarding, Career/ Role Transition and Succession planning
     </p>
     <br>
     <h5>
       Join BCS
     </h5>
     <p>
       If you are looking for challenging opportunities in Executive Search or Organizational /
Leadership consulting as a partner, we offers exciting opportunities across all levels from
researcher, consultant, Practice Leader to Partner. Please write to us at : <a>solutionsbizzcon@gmail.com</a>
     </p>
  </div>
      <div class="wrapper">
        <NuxtLink to="/jobs/post"><button href="/jobs/post">Submit your CV</button></NuxtLink>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.all{
  background: url(https://images.unsplash.com/photo-1436262513933-a0b06755c784?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80);
  text-align: left;
  color: white;
  padding: 30px;
  width: 100%;
}

.all h2{
  font-size: 40px;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.all p{
    font-size: 20px;

}

.view{
  background: rgb(252,140,20);
  height: 10px;
  width: 80px;
}
.wrapper{
  padding: 20px;
}
.wrapper button{
  border: none;
  padding: 10px;
  color: black;
  border-radius: 5px;

  background: rgb(252,140,20);
}
.info{
  padding: 20px;
  text-align: center;
}

.info p{
      font-size: 19px;
      text-align: justify;

}
.info h5{
    text-align: justify;
     color: rgb(252,140,20);
}
</style>