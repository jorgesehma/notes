# notes

<script>
        $(document).ready(function() {
            $( "a" ).hover(
                function() {
                    $( this ).addClass('jstree-clicked');
                    $( this ).parent().css('z-index', '2');
                    $('#jstree-default').css('overflow', '');
                }
            );
        });

        /*document.querySelector('.panel-body').addEventListener('mousemove', function(event) {
        const element = document.elementFromPoint(event.pageX, event.pageY);
        if (element.classList.contains('jstree-anchor')) {
            element.setAttribute('title', element.innerText);
            element.setAttribute('data-toggle', 'tooltip');
        }
        setTimeout(function() {
            $('[data-toggle="tooltip"]').tooltip({
                placement: 'left',
                trigger: 'hover',
                delay:{ hide:1 }
            });
        }, 500);
    });*/
    </script>
