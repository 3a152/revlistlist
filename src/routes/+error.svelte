<script>
    export let error;
    export let status;
</script>

<div class="box">
  <h1>{status}</h1>
  <p>{error?.message ?? "how tf are you here???????"}</p>
  <img src="/images/sadblob.png" alt="crying blobmoji" class="d-block mx-auto rounded">
   <a href="/" class="btn btn-success mt-3">go back</a>
</div>

<style>
    .box {
        max-width: 500px;
        margin: 50px auto;
        border: 2px solid #444;
        border-radius: 10px;
        background-color: #1a1a1a;
        color: white;
        text-align: center;
    }
</style>