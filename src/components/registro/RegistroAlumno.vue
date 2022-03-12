<template>
  <div class="RegistroAlumno">
<div class="container">

    <div class="row">
        <div class="col-5">
            Registro, Listas y Pagos
        </div>
        <div class="col-7 float-righ">
            <div class="card">
                <div class="card-header bg-primary text-light">
                    <label class="text-light">Registro de Alumnos</label>
                </div>
                <div class="card-body">
                    <form>
                        <div class="row">
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Nombre Completo:</label>
                                <input type="text" class="form-control" placeholder="First name">
                            </div>
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Fecha de nacimiento:</label>
                                <input type="date" class="form-control" placeholder="Last name">
                            </div>
                        </div>
                        <div class="row">
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Edad:</label>
                                <input type="text" class="form-control" placeholder="First name">
                            </div>
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Elegir Disciplina:</label>
                                <input type="text" class="form-control" placeholder="Last name">
                            </div>
                        </div>
                        <div class="row">
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Horario:</label>
                                <input type="time" class="form-control" placeholder="First name">
                            </div>
                            <div class="form-group col-md-6">
                                <label for="inputEmail4">Correo:</label>
                                <input type="text" class="form-control" placeholder="Last name">
                            </div>
                        </div>
                        
                        <div class="form-row">
                            <div class="form-group col-md-12">
                                <button class="btn btn-primary" type="submit">Guardar</button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
            
    </div>

    
</div>
  </div>
</template>

<script>

export default {
  components: { },
  name: 'RegistroAlumno',
  props: {
    msg: String
  }
}
</script>