<script>
  const resumePath = "../../assets/StephenParkResume06092019.pdf";
  const headerSlogan = "Software Engineer, Web Developer";
</script>

<style>
  .navBar {
    display: flex;
    white-space: nowrap;
    flex-flow: nowrap row;
    justify-content: space-between;
    align-items: center;
    margin: auto;
    padding: 20px;
    height: 64px;
  }

  .navBar-left {
    flex: .5;
    display: flex;
    flex-flow: nowrap row;
  }

  .navBar-left h1 {
    -webkit-transition: color .5s ease-out;
    -moz-transition: color .5s ease-out;
    -o-transition: color .5s ease-out;
    transition: color .5s ease-out;
  }

  .navBar-left h1:hover {
    color: #ccc;
  }

  .navBar-right {
    display: flex;
    flex-flow: nowrap row;
  }

  .navBar-right a {
    -webkit-transition: color .5s ease-out;
    -moz-transition: color .5s ease-out;
    -o-transition: color .5s ease-out;
    transition: color .5s ease-out;
    color: #181818;
    margin: 10px;
  }

  .navBar-right a:hover {
    color: #ccc;
  }

  .headerContainer {
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(224deg, #00f2ff, #e700ff, #ffb600);
    background-size: 200% 200%;
    -webkit-animation: GradientAnimation 18s ease infinite;
    -moz-animation: GradientAnimation 18s ease infinite;
    animation: GradientAnimation 18s ease infinite;
    height: 300px;
  }

  .headerContainer h1 {
    color: #e6e6e6;
  }
</style>

<div class="navBar">
  <div class="navBar-left">
    <a href="/"><h1>Stephen Park</h1></a>
  </div>
  <div class="navBar-right">
    <a href={resumePath}>Resume</a>
  </div>
</div>
<div class="headerContainer">
  <h1>{headerSlogan}</h1>
</div>
