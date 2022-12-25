To Make html elements center by horizontally and verically.

heer is the html code
<div class="content">
  <div class="child">  
    Center Text
  </div>
</div>

Here is the css code
<style>
.content{
  width:1140px;
  margin:0 auto;  
}
.child{
  display:flex;
  align-items:center;
  justify-content:center;
  height:100vh;
}
</style>
