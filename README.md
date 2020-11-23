# JQuery - Basic Hide/Show Effects

Give button an id and the related element a class that matches.

<script>
jQuery( document ).ready(function( $ ) {
  $('.buttonclass').click(function() {
    let target = $(this).attr('id');
    $('.elementclass).hide();
    $('.' + target).fadeIn();
  });
});
</script>
