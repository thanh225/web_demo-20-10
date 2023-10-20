
<marquee id="marq" scrollamount="3" loop="50" scrolldelay="0" class="hovergallery">
    <img src="img/h1.jpg" width="300" height="300"/> </a>
    <img src="img/lc1.jpg" width="300" height="300"/> </a>
    
    <img src="img/h2.jpg" width="300" height="300"/> </a>
    <img src="img/lc2.jpg" width="300" height="300"/> </a>
    
    <img src="img/h3.jpg" width="300" height="300"/> </a>
    <img src="img/lc3.jpg" width="300" height="300"/> </a>
    
    <img src="img/h4.jpg" width="300" height="300"/> </a>
    <img src="img/lc4.jpg" width="300" height="300"/> </a>
    
    <img src="img/h5.jpg" width="300" height="300"/> </a>
    <img src="img/lc5.jpg" width="300" height="300"/> </a>
    
    <img src="img/h6.jpg" width="300" height="300"/> </a>
    <img src="img/lc6.jpg" width="300" height="300"/> </a>
    
    <img src="img/h7.jpg" width="300" height="300"/> </a>
    <img src="img/lc7.jpg" width="300" height="300"/> </a>
    
    <img src="img/h9.jpg" width="300" height="300"/> </a>
    <img src="img/lc9.jpg" width="300" height="300"/> </a>
    
    <img src="img/h10.jpg" width="300" height="300"/> </a>
    <img src="img/lc10.jpg" width="300" height="300"/> </a>
    
    <img src="img/lc8.jpg" width="300" height="300"/> </a>
    
</marquee>


<!--Chuyển trang sau 374s(Đồng thời hết bài hát-->
<script type="text/javascript"> 
	var jgt = 10; document.getElementById('time').innerHTML = jgt; 
	function stime(){
		document.getElementById('time').innerHTML = jgt; 
		jgt = jgt - 1; 
		if(jgt == 0){
			clearInterval(timing); 
			location = 'Index.html';
			} 
		} 
	var timing = setInterval("stime();",37400); 
</script>

<script src="js/jquery-3.2.1.min.js"></script>
<script src="js/bootstrap.min.js"></script>
</body>
</html>
