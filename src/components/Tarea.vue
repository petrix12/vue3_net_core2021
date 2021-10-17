<template>
    <div>
        <h1 class="display-4 text-center">Lista de tareas</h1>
        <hr>
        <div class="row">
            <div class="col-lg-8 offset-lg-2">
                <div class="card mt-4">
                    <div class="card-body">
                        <div class="input-group">
                            <input type="text" class="form-control form-control-lg" placeholder="Agregar tarea">
                            <div class="input-group-append">
                                <button class="btn btn-success btn-lg">Agregar</button>
                            </div>
                        </div>
                        <br>
                        <ul class="list-group">
                            <li class="list-group-item d-flex justify-content-between">
                                <div>
                                    <span class="cursor">
                                        <i class="far fa-circle"></i>
                                    </span>
                                    Tareas Soluciones++
                                </div>
                                <span class="text-danger cursor">
                                    <i class="fas fa-trash-alt"></i>
                                </span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Tarea'
    }
</script>

<style scoped>
    .cursor {
        cursor: pointer;
    }
</style>