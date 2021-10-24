<script>
    export let title;
    export let item1;
    export let item2;
    export let item3;
    export let hobby1;
    export let hobby2;
    export let hobby3;
    export let personality1;
    export let personality2;
    export let personality3;
</script>

<div class="p-5">
    <div class="card">
        <div class="card-body">
            <h3>{title}</h3>
            <p>Name: {item1}</p>
            <p>Age: {item2}</p>
            <p>School: {item3}</p>
        </div>
      </div>
</div>

<div class="p-5">
    <div class="card">
        <div class="card-body">
            <h3>Hobbies</h3>
            <p>{hobby1}</p>
            <p>{hobby2}</p>
            <p>{hobby3}</p>
        </div>
      </div>
</div>

<div class="p-5">
    <div class="card">
        <div class="card-body">
            <h3>Personality</h3>
            <p>{personality1}</p>
            <p>{personality2}</p>
            <p>{personality3}</p>
        </div>
      </div>
</div>

<style>
    .card{
        text-align: center;
    }
</style>
