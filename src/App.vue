<script setup>
</script>

<template>
 <div class="container">
  <div class="row mt-4">
    <div class="col-md-5">
      <select class="form-select" aria-label="Default select example">
  <option selected>Все машины </option>
  <option value="1">BMW</option>
  <option value="2">Mersedess</option>
  <option value="3">Audi</option>
      </select> 
    </div>
    <div class="col-md-5">
      <input type="text" class="form-control" placeholder="Search by name...">
    </div>
    <div class="col-md-2">
      <button type="button" class="btn btn-warning">Reset</button>
    </div>
  </div>






  <div class="row row-cols-1 row-cols-md-3 g-4 mt-4 ">
  <div class="col">
    <div class="card h-100">
      <img src="https://steamuserimages-a.akamaihd.net/ugc/1829033806571764401/8FEB040EBE4208BA1C5D7B6D29FE828FE994138C/?imw=512&amp;imh=288&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">BMW M5 competition</h5>
        <p class="card-text">car</p>
      </div>
      <div class="card-footer">
        <button type="button" class="btn btn-outline-info me-2">Detail</button>
        <button type="button" class="btn btn-outline-success">App</button>
      </div>
    </div>
  </div>




  <div class="card h-100">
    <div class="col">
      <img src="https://i.pinimg.com/originals/07/b6/a4/07b6a40bdafc0a6f282fcdd7e5db41dc.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mercedes cls 63 amg</h5>
        <p class="card-text">car</p>
      </div>
      <div class="card-footer">
        <button type="button" class="btn btn-outline-info me-2">Detail</button>
        <button type="button" class="btn btn-outline-success">App</button>
      </div>
  </div>
</div>





  <div class="col">
    <div class="card h-100">
      <img src="https://avatars.mds.yandex.net/i?id=bdeabc28207ce61d34a595e99f1e9fc5_l-5649169-images-thumbs&n=13" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Audi RS5</h5>
        <p class="card-text">car</p>
        <div class="card-footer">
           <button type="button" class="btn btn-outline-info me-2">Detail</button>
           <button type="button" class="btn btn-outline-success">App</button>
      </div>
      </div>
    </div>
  </div>




  <div class="col">
    <div class="card h-100">
      <img src="..." class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text"></p>
        <div class="card-footer">
        <button type="button" class="btn btn-outline-info me-2">Detail</button>
        <button type="button" class="btn btn-outline-success">App</button>
      </div>
      </div>
    </div>
  </div>
</div>
 </div>



</template>
<style scoped>
.card {
  border-radius: 15px; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
  transition: transform 0.3s ease, box-shadow 0.3s ease; 
}

.card:hover {
  transform: translateY(-5px); 
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2); 
}

.card-img-top {
  border-radius: 15px 15px 0 0; 
  object-fit: cover; 
  height: 200px; 
}

.card-body {
  padding: 15px; 
}

.card-title {
  font-size: 1.2rem; 
  font-weight: bold;
  color: #333; 
}

.card-text {
  font-size: 1rem;
  color: #666; 
}

.card-footer {
  background-color: #f8f9fa; 
  border-top: 1px solid #ddd; 
}

.card-footer .btn {
  font-size: 0.9rem;
  transition: background-color 0.3s ease;
}

.card-footer .btn:hover {
  background-color: #ddd; 
}


@media (max-width: 768px) {
  .row-cols-md-3 {
    row-gap: 20px;
  }
}
</style>