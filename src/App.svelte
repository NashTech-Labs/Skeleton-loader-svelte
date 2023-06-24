<script>
  import Skeleton from "svelte-skeleton-loader";
</script>

<style>
</style>

<h1> Types of skeleton loader in svelte</h1>
<br/>
<br/>
<h2>Single-line skeleton Loader</h2>
<Skeleton/>
<br/>
<h2>Multiple-line skeleton Loader</h2>
<Skeleton count={5}/>
<br/>

<h2>Skeleton Loader With Different Width</h2>
<div>
<Skeleton width={100}/><br>
<Skeleton width={200} /><br>
<Skeleton width={300} /><br>
<Skeleton width={400} /><br>
</div>
<br/>
<h2>Skeleton Loader With Different Height</h2>
<div>
  <Skeleton width={200}  height={30}/><br>
  <Skeleton width={200} height={40} /><br>
  <Skeleton width={200} height={50} /><br>
  <Skeleton width={200} height={60} /><br>
</div>
<br/>
<h2>Skeleton loader in circular form</h2>
<div>
  <Skeleton circle={true} height={80} width={80} />
</div>






