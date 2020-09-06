# HTML Tree of Trafalgar Template
## Main layout
    body
        header
            nav.top-nav
        main
            section.banner
            section.services
            section.providers
            section.download
            section.testimonials
            section.blog
        footer
            section.app-footer

## SECTION TOP-NAV
    nav.top-nav
        div.container
            div.row
                div.col
                    a.top-nav__link-logo
                        img.top-nav__logo
                div.col
                    ul.top-nav__menu
                        li*5
                            a

## SECTION BANNER
    section.banner
        div.container
            div.row
                div.col
                    div.banner__content
                        h1.banner__title
                        p.banner__description
                        button.button
                div.col
                    div.banner__image
                        img

## SECTION SERVICES
    section.services
        div.container
            
            div.services__introduction
                h2.services__title
                p.services__description
            div.row
                div.col
                    div.services__item*6
                        img.services__item-image
                        h3.services__item-title
                        p.services__item-description             
                div.services__link             
                    a

## SECTION PROVIDERS
    section.providers
        div.container
            div.row
                div.col
                    img.providers__image
                div.col
                    div.providers__content
                        h2.providers__title
                        p.providers__description
                        a.providers__link

## SECTION - DOWNLOAD
    section.download
        div.container
            div.row
                div.col
                    div.download__content
                        h2.download__title
                        p.download__description
                        button.button--outline
                div.col
                    img.download__image

## SECTION - TESTIMONIALS
    section.testimonials
        div.container
            div.testimonials__title
                h2.testimonials__title
            div.row
                div.col
                    div.testimonials__profile
                        div.testimonials__image
                            img
                        div.testimonials__info
                            h4.testimonials__name
                            p.testimonials__jobs
                div.col
                    p.testimonials__content

## SECTION - BLOG
    section.blog
        div.container
            div.blog__title
                h2
            div.row
                div.col
                    ul.blog__content
                        li
                            img.blog__image
                            h3.blog__heading
                            p.blog__description
                            a.blog__link-item 
                                i
            div.blog__link
                a        

## FOOTER
    footer
        section.app-footer
            div.container
                div.row
                    div.col
                        img.app-footer__logo
                        p.app-footer__description
                        p.app-footer__copyright
                    div.col
                        ul.app-footer__list-items
                            li*3
                                div.app-footer__item
                                    h4.app-footer__heading
                                    ul.app-footer__item
                                        li*4
                                            a                                                