# indext.html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript</title>
</head>
<body>
    <h1>Список справ</h1>
    <input Id="Deal">
    <button onclick="add_to_list()">Додати</button>
    <ul id="list"></ul>
</body>
<script>
    function add_to_list(){
        text = document.getElementById("Deal").value 
        document.getElementById("list").innerHTML+="<li>"+text+"</li>"}
</script>
</html>
