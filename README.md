# 4.-HAFTA-ARZU-YAZGAN
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 10px;

    
    }

    th, td {
      
      padding:3px;
      text-align: center;
      }

    th {
      background-color:black;
    }

    img {
      max-width:600px;
      height:200px;
      margin-bottom:10px 
      
    }

    h1 {
    
     text-align: center
     
     </style>
  <title>3x5 Görsel Tablo</title>
</head>
<body>

 <h1>RESİM GALERİSİ</h1>
  <table>
    
    <tr id="tablo1">
      <td><img src="https://source.unsplash.com/random/800x600?sig=1" alt="Resim 1"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=2" alt="Resim 2"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=3" alt="Resim 3"></td>
    </tr>
    </tr>
   </table>

    <table id="tablo2">
    
    <tr>
     <td><img src="https://source.unsplash.com/random/800x600?sig=4" alt="Resim 4"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=5" alt="Resim 5"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=6" alt="Resim 6"></td>
    
    </tr>
   </table>

 <table id="tablo3">
    
    <tr>
      <td><img src="https://source.unsplash.com/random/800x600?sig=7" alt="Resim 7"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=8" alt="Resim 8"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=9" alt="Resim 9"></td>
    
    </tr>
   </table>

   <table id="tablo4">
    
    <tr>
      <td><img src="https://source.unsplash.com/random/800x600?sig=10" alt="Resim 10"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=11" alt="Resim 11"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=12" alt="Resim 12"></td>
    
    </tr>
   </table>

    
    <table id="tablo5">
    
    <tr>
      <td><img src="https://source.unsplash.com/random/800x600?sig=13" alt="Resim 13"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=14" alt="Resim 14"></td>
      <td><img src="https://source.unsplash.com/random/800x600?sig=15" alt="Resim 15"></td>
    
    </tr>
   </table>

    <script>
    
    let currentTableIndex = 1;

   
    var id={tablo1,tablo2,tablo3,tablo4,tablo5}
 function showTable(index) {
      document.getElementById(`tablo${currentTableIndex}`).style.display = 'none';
      currentTableIndex = index;
      document.getElementById(`tablo${index}`).style.display = 'table';

    }

</script>


  

</body>
</html>
