<template>
  <div class="con">
      <div class="all">
        <h3>Submit your CV</h3>
        <div class="view"></div>
      </div>
       <div class="info">
         <p>
        You may be a senior executive with diverse experience, understand changing talent
        landscape with ability for business development and networking with senior professionals or
        you may be already an executive search professional, with a specialist area of expertise.          </p>
        <br>
         <p>Only a select few mandates being handled by us are posted on our website and other online platforms. A vast majority of jobs aren’t in the public domain. Be a part of our searchable centralized database by sending us your details.</p>
         <br>
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
          
        <p>
          Submit your CV through below form:
        </p>
       </div>
       <div class="forms">
         <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfK6Dm_hZi44dQyD9i1xu7XjDUOB6J7ytql_CYeTBweqQVe7w/viewform?embedded=true" width="100%" height="2536" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
       </div>
      <!-- <div class="form">
        <p>(*) All fields are mandatory</p>
        <form action="">
          <input type="text" placeholder="First Name* " required>
          <input type="text" placeholder="Last Name*" required>
          <select name="Gender" id="gender">
            <option value="gen">Gender</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
          </select>
          <label for="DOB">Date of Birth:</label>
          <input type="date" id="dob" name="dob">
          <input type="email" placeholder="Email Id*" required>
          <input type="number" placeholder="Mobile No*" required>
          <input type="text" placeholder="Location*" required>
          <input type="text" placeholder="Company*" required>
          <input type="text" placeholder="Designation*" required>
          <input type="text" placeholder="Experience in Years*" required>
          <input type="text" placeholder="Current Salary (INR)*" required>
          <select name="Eductaion" id="edu">
            <option value="Edu">Education</option>            
            <option value="ba">B.A</option>
            <option value="barch">B.Arch</option>
            <option value="bcom">B.COM</option>
            <option value="bba">B.B.A</option>
            <option value="bed">B.Ed</option>
            <option value="bpharma">B.Pharma</option>
            <option value="be">B.E/B.Tech</option>
          </select>
          <input type="text" placeholder="Function*" required>
          <input type="text" placeholder="Industry*" required>
          <input type="text" placeholder="Skills*" required>
          <label for="cv">Resume:</label>
          <input type="file" placeholder="Upload Resume">

          <div class="submit">
            <button>submit</button>
          </div>
        </form>
      </div> -->
      
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
.form{
    padding: 20px;
    
}
.form form{
    display: flex;
    flex-direction: column;
    
}

.form form input{
  padding: 10px;
  margin: 10px;
  width: 600px;
  
  border: none;
  border-bottom:1px solid black ;
}
.form form select{
    padding: 10px;
      margin: 10px;
  width: 600px;


}
.form form label{
   padding: 10px;

}

.submit{
  padding: 15px;
}

.submit button{
  border: none;
  padding: 20px;
  color: white;
  border-radius: 5px;

  background: black;
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

@media screen and (max-width: 700px) {
  
.form form input{

  width: 100%;
  
}
.form form select{

  width: 100%;


}
  
}


</style>