<template>
    <div>
        <h1 class="display-4 text-center">Lista de tareas</h1>
        <hr>
        <div class="row">
            <div class="col-lg-8 offset-lg-2">
                <div class="card mt-4">
                    <div class="card-body">
                        <div class="input-group">
                            <input 
                                type="text"
                                v-model="tarea"
                                class="form-control form-control-lg" 
                                placeholder="Agregar tarea"
                            >
                            <div class="input-group-append">
                                <button 
                                    class="btn btn-success btn-lg"
                                    v-on:click="agregarTarea()"
                                >Agregar</button>
                            </div>
                        </div>
                        <br>
                        <ul class="list-group">
                            <li 
                                v-for="(tarea, index) of listTareas" :key="index"
                                class="list-group-item d-flex justify-content-between"
                            >
                                <div>
                                    <span class="cursor">
                                        <i class="far fa-circle"></i>
                                    </span>
                                    {{ tarea.nombre }}
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
        name: 'Tarea',
        data() {
            return {
                tarea: '',
                listTareas: []
            }
        },
        methods: {
            agregarTarea() {
                const tarea = {
                    nombre: this.tarea,
                    estado: false
                }
                this.listTareas.push(tarea)
                this.tarea = ''
            }
        }
    }
</script>

<style scoped>
    .cursor {
        cursor: pointer;
    }
</style>