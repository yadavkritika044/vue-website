<template>
  <section class="protfolio">
    <h1>Portfolio</h1>
    <p>These are suppose to be sample projects</p>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-head">
              <img
                alt="Vue logo"
                class="rounded-circle img-custome"
                src="https://firebasestorage.googleapis.com/v0/b/ad-bot-e026e.appspot.com/o/IMG-20200805-WA0028.jpg?alt=media&token=a449869b-cd20-4df8-8c91-0b7405396f4e"
              />
              <h2>web project</h2>
            </div>
            <hr />
            <div class="card-body">
              <p>
                vue js uses three code html,css and javascript for its
                framework.
              </p>
              <button type="button" class="btn btn-outline-secondary">
                More
              </button>
            </div>
          </div>
          <br />
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-head">
              <img
                alt="Vue logo"
                class="rounded-circle img-custome"
                src="https://i.pinimg.com/originals/4a/70/56/4a70563234301578c158dc142384a1c3.png"
              />
              <h2>web project</h2>
            </div>
            <hr />
            <div class="card-body">
              <p>Merging of three codes makes project very smooth.</p>
              <button type="button" class="btn btn-outline-secondary">
                More
              </button>
            </div>
          </div>
          <br />
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-head">
              <img
                alt="Vue logo"
                class="rounded-circle img-custome"
                src="https://cdn.mos.cms.futurecdn.net/wH5y2PkWhCxqKBje8rBp5e.jpg"
              />
              <h2>web project</h2>
            </div>
            <hr />
            <div class="card-body">
              <p>javascript render html code and html elements.</p>
              <button type="button" class="btn btn-outline-secondary">
                More
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
    <script>
export default {
  name: "card",
};
</script>
       <style>
.protfolio {
  background-color: #34345238;
  padding-top: 8%;
  padding-bottom: 15%;
  /* padding:15% */
}
.img-custome {
  width: 140px;
  height: 140px;
  margin-top: 15px;
}
</style>
        
        
