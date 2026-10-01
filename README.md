<section id="registro" class="py-5 bg-light">

  <div class="container">

    <div class="row justify-content-center">

      <div class="col-md-6 bg-white p-4 p-md-5 rounded-3 shadow-sm">

        

        <h2 class="h3 fw-bold mb-3">Solicitá más información</h2>

        <p class="text-muted small mb-4">Completá el formulario y nos pondremos en contacto en menos de 24 hs.</p>



        <!-- Redirección simulada a Thank You Page al enviar -->

        <form action="gracias.html" method="GET">

          

          <div class="mb-3">

            <label for="nombre" class="form-label font-weight-bold">Nombre completo *</label>

            <input type="text" class="form-control" id="nombre" name="nombre" placeholder="Ej. Ana Pérez" required>

          </div>



          <div class="mb-3">

            <label for="email" class="form-label">Correo electrónico *</label>

            <input type="email" class="form-control" id="email" name="email" placeholder="nombre@empresa.com" required>

          </div>



          <div class="mb-3">

            <label for="interes" class="form-label">¿Qué servicio te interesa?</label>

            <select class="form-select" id="interes" name="interes">

              <option selected value="estrategia">Estrategia Digital</option>

              <option value="redes">Gestión de Redes Sociales</option>

              <option value="publicidad">Publicidad Online (Ads)</option>

            </select>

          </div>



          <div class="form-check mb-4">

            <input class="form-check-input" type="checkbox" value="" id="terminos" required>

            <label class="form-check-label small text-muted" for="terminos">

              Acepto la política de privacidad y el envío de información.

            </label>

          </div>



          <!-- CTA de Envío -->

          <button type="submit" class="btn btn-primary w-100 py-2 fw-bold">

            Enviar solicitud

          </button>

          

        </form>



      </div>

    </div>

  </div>

</section>
