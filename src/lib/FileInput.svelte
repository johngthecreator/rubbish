<script>
let files;
let base64;
function getBase64() {
   var reader = new FileReader();
   reader.readAsDataURL(files[0]);
   reader.onload = function () {
     base64 = reader.result;
   };
   reader.onerror = function (error) {
     console.log('Error: ', error);
   };
}

const readFile = () => {
    var reader = new FileReader();
    reader.readAsDataURL(base64);
}



</script>
<input bind:files type="file" />
<button on:click={getBase64}>Log File</button>
<button on:click={readFile}>Read File</button>