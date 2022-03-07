<template>
    <div class="container-fluid p-0 d-grid bg-bodyy-color">
        <!-- d-flex justify-content-around mt-5 bg-info -->
             <h1 class="mt-3">Shop</h1>
            <div class="row mt-5">

              
                <div  class="col ">
                    <h2 class="text-center text-decoration-underline">Productos</h2>

                    <div class="col-md text-center bg-card  mt-5">
                        <img class="img-fluid" src="@/assets/images/shop1.png" alt="imageone">
                        <h3>Cristal terraza</h3>


                        <button class=" btn btn-success">Añadir al Carrito</button>
                    </div>

                    <div class="bg-card col-md text-center bg-bg-card mt-4">
                        <img src="@/assets/images/shop2.jpg" alt="imagetwo">
                        <h3>Cristales templados</h3>

                        <button class="btn btn-success">Añadir al Carrito</button>
            
                    </div>
            
            
                    <div class=" col-md text-center bg-card mt-4" >
                        <img src="@/assets/images/shop3.jpg" alt="imagethree">
                        <h3>Cristales antireflectantes</h3>


                        <button class="btn btn-success">Añadir al Carrito</button>
            
                    </div>
                    <div class="bg-card col-md text-center  bg-bg-card mb-5 " >
                        <img src="@/assets/images/shop1.png" alt="imagefour">
                        <h3>Cristal de recambio</h3>

                        <button class="btn btn-success">Añadir al Carrito</button>
                    </div>

                </div>
                <div class="col float-end">
                    <h2 class="text-center text-decoration-underline">Carrito</h2>

                    <div class="mt-5">
                        <table class=" table table w-100">
                            <thead>
                                <tr>
                                    <th>ID</th>
                                    <th>Producto</th>
                                    <th>Precio</th>
                                </tr>
                            </thead>
                        </table>
                        <p class="fw-bold text-center">La cesta esta esta vacía</p>
                    </div>

                </div>

            </div>

    </div>
</template>