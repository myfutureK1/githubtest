<main>
  <div class="wrapper">
    <article class="flow">
      <h1>Extrinsic sizing vs intrinsic sizing</h1>
      <figure class="callout">
        <p>
          Notice that when the box is using <strong>extrinsic sizing</strong>, there’s
          a limit of how much content you can add before it overflows out of the box’s
          bounds. This makes the word, “awesome”, overflow.
        </p>
      </figure>
      <label class="toggle" for="intrinsic-switch">
        <span class="toggle__label">Turn on intrinsic sizing</span>
        <input type="checkbox" role="switch" class="toggle__element" id="intrinsic-switch" />
        <div class="toggle__decor" aria-hidden="true">
          <div class="toggle__thumb"></div>
        </div>
      </label>
      <p class="awesome" data-element="awesome">CSS is awesome</p>
    </article>
  </div>
</main>
