# GramBanglar-Food-Grocery
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>গ্রামবাংলার ঐতিহ্যবাহী খাবার</title>

<style>
body{
margin:0;
font-family:Arial;
background:#f4f4f4;
}

/* HEADER */
header{
background:linear-gradient(90deg,#0f8b3d,#20c997);
color:white;
padding:20px;
text-align:center;
}

header h1{
margin:0;
font-size:28px;
}

header p{
margin:5px 0 0;
}

/* HERO */
.hero{
background:white;
text-align:center;
padding:30px;
}

.hero h2{
color:#0f8b3d;
}

.btn{
background:#ff6600;
color:white;
padding:12px 20px;
border-radius:5px;
text-decoration:none;
display:inline-block;
margin-top:10px;
}

/* PRODUCT GRID */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:15px;
padding:20px;
}

.card{
background:white;
border-radius:10px;
padding:15px;
box-shadow:0 2px 8px rgba(0,0,0,0.1);
text-align:center;
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card h3{
color:#333;
}

.price{
color:#0f8b3d;
font-weight:bold;
margin:5px 0;
}

.order{
background:#25D366;
color:white;
padding:8px 12px;
border:none;
border-radius:5px;
cursor:pointer;
margin-top:10px;
}

/* FOOTER */
footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}

.badge{
background:#ff6600;
color:white;
padding:5px 10px;
border-radius:20px;
font-size:12px;
display:inline-block;
margin-top:5px;
}
</style>
</head>

<body>

<header>
<h1>🌾 গ্রামবাংলার ঐতিহ্যবাহী খাবার</h1>
<p>গ্রামের স্বাদ এখন আপনার ঘরে</p>
<span class="badge">🚚 ২৪ ঘন্টার মধ্যে ডেলিভারি (ঢাকা)</span>
</header>

<div class="hero">
<h2>খাঁটি দেশি পণ্য অনলাইনে অর্ডার করুন</h2>
<p>পাবনার ঘি • মধু • খেজুরের গুড় • আখের গুড়</p>
<a class="btn" href="#products">🛒 এখনই শপিং করুন</a>
</div>

<section class="products" id="products">

<div class="card">
<h3>পাবনার খাঁটি ঘি</h3>
<p class="price">৳ 750 / 500ml</p>
<button class="order">WhatsApp অর্ডার</button>
</div>

<div class="card">
<h3>দেশি মধু</h3>
<p class="price">৳ ৫০০ / 500gm</p>
<button class="order">WhatsApp অর্ডার</button>
</div>

<div class="card">
<h3>খেজুরের গুড়</h3>
<p class="price">৳ ৪৫০ / 1kg</p>
<button class="order">WhatsApp অর্ডার</button>
</div>

<div class="card">
<h3>আখের গুড়</h3>
<p class="price">৳ ২৫০ / 1kg</p>
<button class="order">WhatsApp অর্ডার</button>
</div>

</section>

<footer>
<p>💳 বিকাশ | নগদ | ব্যাংক ট্রান্সফার</p>
<p>📞 যোগাযোগ: 01941181222</p>
<p>© 2026 গ্রামবাংলার ঐতিহ্যবাহী খাবার</p>
</footer>

</body>
</html>
