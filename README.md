# Minfle

Minimal static grid on the flex display

## Use 

In Project variables indicating the width for tablet and desktop.

Default width:  
        $tablet_container  = 46.875em (~ 750px at font-size: 16px)  
        $desktop_container = 73.125em (~1170px at font-size: 16px)

### Class
  + .container (limited width)
  + .row
  + .col-1 ... - 12 (Static template)
  + .col-xs-1 ... - 12
  + .col-sm-1 ... - 12 (Start at min-width $tablet_container)
  + .col-md-1 ... - 12 (Start at min-width $desktop_container)

### Example
      <div class="container">
        <div class="row">
          <div class="col-3">
            ... content ...
          </div>
          <div class="col-2">
            ... content ...
          </div>
          <div class="col-7">
            ... content ...
          </div>
        </div>
      </div>