<script>
let files;
let base64;
function getBase64() {
   var reader = new FileReader();
   reader.readAsDataURL(files[0]);
   reader.onload = function () {
     base64 = reader.result;
     console.log(reader.result);
   };
   reader.onerror = function (error) {
     console.log('Error: ', error);
   };
}


</script>
<input bind:files type="file" />
<button on:click={getBase64}>Log File</button>
<a href="{base64}" download="test.jpg">Download</a>