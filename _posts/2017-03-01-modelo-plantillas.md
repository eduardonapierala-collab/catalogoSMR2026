---
title: "Modelos de trajes"
layout: post
---

<nav class="uk-navbar-container">
    <div class="uk-container uk-text-bold">
        <div uk-navbar>

            <div class="uk-navbar-center">

                <div class="uk-navbar-center-left">
                    <ul class="uk-navbar-nav">
                        <li class="uk-active"><a href="#">Trajes</a></li>
                        <li>
                            <a href="#">Parent</a>
                            <div class="uk-navbar-dropdown">
                                <ul class="uk-nav uk-navbar-dropdown-nav">
                                    <li class="uk-active"><a href="#">Active</a></li>
                                    <li><a href="#">Item</a></li>
                                    <li><a href="#">Item</a></li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </div>
                <a class="uk-navbar-item uk-logo" href="index.html"><img src="image/rcs/logo-SMR-negro.PNG" width="64.12" height="90" alt=""></a>
                <div class="uk-navbar-center-right">
                    <ul class="uk-navbar-nav">
                        <li><a href="#">Item</a></li>
                        <li><a href="#">Item</a></li>
                    </ul>
                </div>

            </div>

        </div>
    </div>
</nav>






<div class="uk-grid-match uk-grid-small uk-text-center" uk-grid>


<!--<img src="{{ '/assets/images/T1910.jpg' | relative_url }}" alt="Descripción de la imagen" style="width: 100%; height: auto;">-->

<div class="uk-width-1-2@m">
    <div class="uk-card uk-card-body ">
        <div>
            <div class="uk-inline uk-dark">
            <img src="{{ '/assets/images/T1910.jpg' | relative_url }}" alt="Descripción de la imagen" style="width: 100%; height: auto;">

                <a class="uk-position-absolute uk-transform-center" style="left: 27%; top: 27%" href="#" uk-marker></a>


                        <div uk-drop="mode: click; pos: top-center">
                            <div class="uk-card uk-card-body uk-padding-small">
                                <img src="image/rcs/cuello.jpg" width="150" alt="Detalle 1">
                                <p class="uk-text-small uk-margin-small-top">Cuello</p>
                            </div>
                        </div>

                    <a class="uk-position-absolute uk-transform-center" style="left: 58%; top: 68%" href="#" uk-marker></a>
                        <div uk-drop="mode: click; pos: top-center">
                            <img src="image/rcs/botones.jpg" width="150" class="uk-border-rounded" alt="Detalle 2">
                        </div>

                    <a class="uk-position-absolute uk-transform-center" style="left: 92%; top: 83%" href="#" uk-marker></a>
                        <div uk-drop="mode: click; pos: top-center">
                            <img src="image/rcs/mangas.jpg" width="150" class="uk-border-rounded" alt="Detalle 2">
                        </div>

                </div>
            </div>


        </div>

    </div>





    <div class="uk-width-1-2@m">

    <div class="uk-card uk-card-default uk-card-body"><h1 class="uk-heading-bullet uk-heading-divider">Detalle</h1>


        <!-- This is a button toggling the modal -->
        <button class="uk-button uk-button-default uk-margin-small-right" type="button" uk-toggle="target: #modal-example">Open</button>

        <!-- This is an anchor toggling the modal -->
        <!--<a href="#modal-example" uk-toggle>Open</a>-->

        <!-- This is the modal -->
        <div id="modal-example" uk-modal>
            <div class="uk-modal-dialog  uk-modal-body">
                <h2 class="uk-modal-title">Detalle</h2>

        <div class="uk-column-1-2 uk-column-divider uk-margin-top">
            <div class="uk-text-right">
                <ul class="uk-list uk-list-striped uk-text-uppercase uk-list-collapse">
                    <li class="uk-text-lead">T1901</li>
                    <li>Botones delantero</li>
                    <li>Botones de manga</li>
                    <li>Bolsillo</li>
                    <li>Solapa</li>
                    <li>Tela en contraste</li>
                    <li>Pespunte</li>
                    <li>Aberturas traseras saco</li>
                    <li>Otro detalle</li>
                </ul>
             </div>

            <div class="uk-text-left">
                <ul class="uk-list uk-list-striped uk-text-uppercase uk-list-collapse">
                    <li class="uk-text-lead">Base 2019</li>
                    <li>2 Botones</li>
                    <li>4 Botones</li>
                    <li>nclinados, de tapas</li>
                    <li>De muesca</li>
                    <li>No aplica</li>
                    <li>No aplica</li>
                    <li>2 laterales</li>
                    <li>No aplica</li>
                </ul>
            </div>
        </div>

            </div>
        </div>


        <hr class="uk-divider-icon">

        <div class="uk-column-1-2 uk-column-divider uk-margin-top">
            <div class="uk-text-right">
                <ul class="uk-list uk-list-striped uk-text-uppercase uk-list-collapse">
                    <li class="uk-text-lead">T1901</li>
                    <li>Botones delantero</li>
                    <li>Botones de manga</li>
                    <li>Bolsillo</li>
                    <li>Solapa</li>
                    <li>Tela en contraste</li>
                    <li>Pespunte</li>
                    <li>Aberturas traseras saco</li>
                    <li>Otro detalle</li>
                </ul>
             </div>

            <div class="uk-text-left">
                <ul class="uk-list uk-list-striped uk-text-uppercase uk-list-collapse">
                    <li class="uk-text-lead">Base 2019</li>
                    <li>2 Botones</li>
                    <li>4 Botones</li>
                    <li>nclinados, de tapas</li>
                    <li>De muesca</li>
                    <li>No aplica</li>
                    <li>No aplica</li>
                    <li>2 laterales</li>
                    <li>No aplica</li>
                </ul>
            </div>
        </div>

        <hr class="uk-divider-icon">




        <div class="uk-position-bottom-center uk-position-small uk-margin-bottom uk-margin-top">
            <ul class="uk-slideshow-nav uk-thumbnav">
                <li uk-slideshow-item="0"><a href="#"><img src="image/rcs/cuello.jpg" width="100" height="67" alt=""></a></li>
                <li uk-slideshow-item="1"><a href="#"><img src="image/rcs/cuello.jpg" width="100" height="67" alt=""></a></li>
                <li uk-slideshow-item="2"><a href="#"><img src="image/rcs/cuello.jpg" width="100" height="67" alt=""></a></li>
            </ul>
        </div>





        <div class="uk-grid-collapse uk-child-width-expand@s uk-text-center uk-margin-large-top" uk-grid>
            <div>
                <div class="uk-background-primary uk-padding uk-light">Item</div>
            </div>
            <div>
                <div class="uk-background-secondary uk-padding uk-light">Item</div>
            </div>
        </div>



        </div>
    </div>  
</div>








[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
