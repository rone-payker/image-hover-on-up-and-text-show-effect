.image-effect{
    position: relative;
}

.image-effect .wp-block-cover{
    background-color: #222;
    overflow: hidden;
}

.image-effect .wp-block-column h2, .image-effect .wp-block-column p, .image-effect .wp-block-column .wp-block-image{
    transition: 1s;
    transition-delay: 0.5s;
    opacity: 0;
}

.image-effect .wp-block-column .wp-block-group{
    transform: scale(1.2);
    transition: 1s ease-in-out;
    opacity: 0;
}

.image-effect .wp-block-cover__image-background{
    transition: 0.8s ease-in;
}

/*hover*/

.image-effect .wp-block-column:hover .wp-block-group {
    transform: scale(0.9);
    opacity: 1;
}

.image-effect .wp-block-column:hover .wp-block-cover__image-background {
    opacity: .6;
    transform: scale(1.5);
}

.image-effect .wp-block-column:hover h2, .image-effect .wp-block-column:hover p, .image-effect .wp-block-column:hover .wp-block-image {
    opacity: 1 !important;
}
