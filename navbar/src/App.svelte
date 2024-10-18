<script>
    
        import { Dropdown } from "bootstrap";
        import "./css/app.css";
        import "./css/custom.css";
    import Navbar from "./features/MainContent/Navbar.svelte";
 
    import MainContent from "./features/MainContent/Info.svelte";
  import ProjectsList from "./features/projects/ProjectsList.svelte";
   
  </script>
  
  <div class="app-container">
    <Navbar />
    <div class="content-wrapper">
      <MainContent />
      
    </div>
    <ProjectsList />
  </div>
  <style global>
    @import url('https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.10.5/font/bootstrap-icons.min.css');
  </style>