# StringBean
The featherweight responsive CSS Framework based on a 16-point system (rather than the traditional 12-point system that other frameworks use) this gives the developer the power to divide the screen up in more finite segments. The extra 4 break points give you greater control over the widths of content on your site. Sometimes, 12 is just too few, especially on a high resolution screen, such as 4K - at 4K String Bean comes into its own! 

In addition to this, String Bean also has 5 breakpoints instead of the traditional 4. You can implement your design with: xsmall, small, medium, large, and xlarge.

## Examples

#### Simple Header Layout

    <header class="container">
      <nav class="row">
        <div class="column xsmall-16 small-16 medium-10 large-11 xlarge-12">
          <h1>
            StringBean
          </h1>
        </div>
        <div class="column xsmall-16 small-16 medium-5 large-4 xlarge-3">
          <p id="Strapline">
            Powering the internet, gently.
          </p>
        </div>
      </nav>
    </header>

#### Buttons

    <a href="/login" class="button normal information">Login</a>
    <a href="/login" class="button normal alert">Register</a>

#### Grid

    <div class="grid">
        <li class="box xsmall-16 small-16 medium-7 large-5 xlarge-3">
            Box #1
        </li>
        
        <li class="box xsmall-16 small-16 medium-7 large-5 xlarge-3">
            Box #2
        </li>
        
        <li class="box xsmall-16 small-16 medium-7 large-5 xlarge-3">
            Box #3
        </li>
    </div>

### Hiding Content Below Breakpoints
You can hide content below certain breakpoints - for instance: hide-below-large will hide the element below the large breakpoint.

    <div class="hide-below-medium">
        Hello world!
    </div>

### Showing Content Below Certain Breakpoints

    <div class="show-below-large">
        Hello World!
    </div>

As simple as that!  You should also check out the button functionality.
