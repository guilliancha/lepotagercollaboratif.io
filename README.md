# lepotagercollaboratif.io

{
  "réglages": {
    "nom": "Site-10-02_2121",
    "currentPage": "index.html",
    "thème": {
      "nom": "mobirise4",
      "title": "Mobirise 4",
      "coiffant": {
        "primaryColor": "# 149dcc",
        "SecondaryColor": "# ff3366",
        "successColor": "# F7ED4A",
        "infoColor": "# 82786E",
        "warningColor": "# 879A9F",
        "dangerColor": "# B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4,25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": 1,5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": vrai,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": [
        "# a9e4a1",
        "# 65bf5c"
      ]
    },
    "chemin": "@ PROJECT_PATH @",
    "siteFonts": [],
    "versionFirst": "4.7.5",
    "uniqCompNum": 14,
    "versionPublish": "4.7.5",
    "favicon": "",
    "noImageResize": "",
    "screenshot": "screenshot.png"
  },
  "pages": {
    "index.html": {
      "réglages": {
        "main": vrai,
        "title": "Accueil",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "Composants": [
        {
          "_modes": {
            "& quand pas (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& quand (@ bg-type = 'color')": {
              "background-color": "@ bg-value"
            },
            "& quand (@ bg-type = 'image')": {
              "background-image": "url (@ bg-value)"
            },
            ".icons-media-container": {
              "display": "flex",
              "justify-content": "center",
              "-webkit-justify-content": "centre",
              "flex-direction": "ligne",
              "-webkit-flex-direction": "ligne",
              "flex-wrap": "wrap",
              "-webkit-flex-wrap": "wrap",
              "padding-top": "4rem",
              ".mbr-iconfont": {
                "font-size": "96px",
                "couleur": "rgb (255, 255, 255)"
              },
              ".icon-block": {
                "padding-bottom": "1rem"
              }
            },
            ".mbr-text": {
              "couleur": "#ffffff"
            },
            ".carte": {
              "padding-bottom": "1.5rem"
            },
            ".mbr-text, .mbr-section-btn": {
              "couleur": "# 232323"
            },
            "H1": {
              "couleur": "# 232323"
            },
            "H5": {
              "couleur": "# 232323"
            }
          },
          "_name": "header12",
          "_customHTML": "<section class = \" header12 \ "group = \" Headers \ "data-bg-video = \" {{bg.type == 'video' && bg.value.url}} \ "plugins = \ "VimeoPlayer \" mbr-class = \ "{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax} \"> \ n \ n <mbr-parameters> \ n <! - - Contrôles des paramètres de blocage (panneau bleu \ "Gear \") -> \ n <input type = \ "checkbox \" title = \ "Full Screen \" name = \ "fullScreen \" coché> \ n <input type = \ "range \" inline title = \ "Top \" name = \ "paddingTop \" min = \ "0 \" max = \ "8 \" step = \ "1 \" value = \ "6 \" condition = \ "fullScreen == false \"> \ n <input type = \ "range \"inline title = \ "Bottom \" name = \ "paddingBottom \" min = \ "0 \" max = \ "8 \" step = \ "1 \" value = \ "6 \" condition = \ "fullScreen == false \ "> \ n \ n <input type = \" checkbox \ "title = \" Afficher le titre \ "name = \" showTitle \ "vérifié> \ n <input type = \" checkbox \ "title = \" Afficher Texte \ "name = \" showText \ "coché> \ n <input type = \" checkbox \ "title = \" Afficher les boutons \ "name = \" showButtons \ "coché> \ n <input type = \" checkbox \ "title = \" Afficher les icônes \ "name = \" showIcons \ "coché> \ n <input type = \" case à cocher \ "title = \" Afficher la flèche \ "name = \" showArrow \ "coché> \ n \ n <select title = \ "Colonnes \" name = \ "cardsCount \ "> \ n <option value = \" 2 \ "> 2 </option> \ n <option value = \" 3 \ "> 3 </option> \ n <option value = \" 4 \ "sélectionné > 4 </option> \ n </select> \ n \ n <fieldset type = \ "background \" name = \ "bg \" parallaxe> \ n <input type = \ "image \" title = \ "Arrière-plan Image \ "value = \" ../_ images / img / 03.jpg \ "parallaxe> \ n <input type = \" color \ "title = \" Background Color \ "value = \" # a9e4a1 \ "selected> \ n <input type = \ "video \" title = \ "Vidéo d'arrière-plan \" value = \ "http: //www.youtube.com/watch? v = uNCr7NdOJgw \"> \ n </fieldset> \ n < type d'entrée = \ "case à cocher \" title = \ "Overlay \ "name = \" overlay \ "checked condition = \" bg.type! == 'color' \ "> \ n <input type = \" color \ "title = \" Overlay Color \ "name = \" overlayColor \ "value = \" # 0f7699 \ "condition = \" overlay && bg.type! == 'color' \ "> \ n <input type = \" range \ "inline title = \" Opacity \ "name = \ "overlayOpacity \" min = \ "0 \" max = \ "1 \" step = \ "0.1 \" value = \ "0.9 \" condition = \ "overlay && bg.type! == 'color' \" > \ n <! - Paramètres du bloc de fin -> \ n </mbr-parameters> \ n \ n <div class = \ "mbr-overlay \" mbr-if = \ "overlay && bg.type! == 'color' \ "mbr-style = \" {'opacity': overlayOpacity, 'background-color':overlayColor} \ "> \ n </div> \ n \ n <div class = \" container \ "> \ n <div class = \" media-container \ "> \ n <div class = \" col-md -12 align-center \ "> \ n <h1 class = \" mbr-section-title pb-3 mbr-white mbr-bold mbr-fonts-style \ "mbr-theme-style = \" display-1 \ " mbr-if = \ "showTitle \"> Le potager collaboratif & nbsp; </h1> \ n <p class = \ "mbr-text pb-3 mbr-white mbr-fonts-style \" mbr-theme-style = \ " display-5 \ "mbr-if = \" showText \ "data-app-selector = \". mbr-text, .mbr-section-btn \ "> Nous sommes une équipe de 8 étudiants ingénieurs à l'IMT Lille Douai qui travaillons à l'élaboration d 'un potager collaboratif à la fois moderne et respectueux des méthodes traditionnelles de jardinage </p> \ n <div class = \ "mbr-section-btn align-center py-2 \" mbr-if = \ "showButtons \" data- toolbar = \ "- mbrBtnMove \" mbr-boutons mbr-theme-style = \ "display-4 \"> <a class = \ "btn btn-md btn-black-outline \" href = \ "http: // imt-lille-douai.fr \ "> Visiter le site de l'IMT </a> </div> \ n \ n <div class = \" icons-media-container mbr-white \ "> \ n <div class = \ "carte col-12 col-md-6 \" mbr-class = \ "{'col-lg-3': cardsCount == '4', 'col-lg-4': cardsCount == '3 '} \ "> \ n <div mbr-if = \" showIcons \ "class = \" icon-block \ ">\ n <a href=\"#bottom\"> \ n <span mbr-icon class = \ "mbr-iconfont mbri-home \" style = \ "color: rgb (35, 35, 35); \"> </span> \ n </a> \ n </div> \ n <h5 mbr-theme-style = \ "display-5 \" mbr-if = \ "showTitle \" class = \ "mbr-fonts- style \ "> Accueil & nbsp; </h5> \ n </div> \ n \ n <div class = \" card col-12 col-md-6 \ "mbr-class = \" {'col-lg-3 ': cardsCount ==' 4 ',' col-lg-4 ': cardsCount ==' 3 '} \ "> \ n <div mbr-if = \" showIcons \ "class = \" icon-block \ "> \ n <a href = \ "index.html \"> \ n <span mbr-icon class = \ "mbr-iconfont mbrib-cloud \" style = \ "color: rgb (35, 35, 35); \"> </ span> \ n </a> \ n </div> \ n <h5 mbr-theme-style = \ "display-5 \" mbr-if = \ "showTitle \" class = \ "mbr-fonts-style \ "> Le projet </h5> \ n </div> \ n \ n <div class = \" card col-12 col-md-6 \ "mbr-class = \" {'col-lg-3': cardsCount == '4', 'col-lg-4': cardsCount == '3'} \ "mbr-if = \" cardsCount> 2 \ "> \ n <div mbr-if = \" showIcons \ "class = \ "icon-block \"> \ n <a href = \ "https: //mobirise.com/ \"> \ n <span mbr-icon class = \ "mbr-iconfont mbri-file \" style = \ "couleur: rgb (35, 35, 35); \ "> </span> \ n </a> \ n </div> \ n <h5 mbr-theme-style = \" display-5 \ "mbr-if = \" showTitle \ "class = \" mbr -fonts-style \ "> Les données & nbsp; </h5> \ n </div> \ n \ n <div class = \" card col-12 col-md-6 \ "mbr-class = \" {'col -lg-3 ': cardsCount ==' 4 ',' col-lg-4 ': cardsCount ==' 3 '} \ "mbr-if = \" cardsCount> 3 \ "> \ n <div mbr-if = \ "showIcons \" class = \ "icon-block \">\ n <a href=\"https://mobirise.com/\"> \ n <span mbr-icon class = \ "mbr-iconfont mbri-letter \" style = \ "couleur: rgb (35, 35, 35); \ "> </span> \ n </a> \ n </div> \ n <h5 mbr-theme-style = \" display-5 \ "mbr-if = \" showTitle \ "class = \ "mbr-fonts-style \"> Nous contacter </h5> \ n </div> \ n </div> \ n </div> \ n </div> \ n </div> \ n \ n <div mbr-if = \ "showArrow \" class = \ "mbr-arrow hidden-sm-down \" aria-hidden = \ "true \"> \ n <a href=\"#next\"> \ n <i classe = \ "mbri-down mbr-iconfont \ "> </i> \ n </a> \ n </div> \ n </section>",
          "_cid": "sclq11S5UF",
          "_anchor": "header12-2",
          "_protectedParams": [],
          "_global": faux,
          "_once": faux,
          "_params": {}
        },
        {
          "_modes": {
            ".navbar": {
              "background": "@menuBgColor",
              "transition": "aucun",
              "min-height": "77px",
              "padding": ".5rem 0"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "une": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& envergure": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "aucun"
              },
              "& une": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0! important",
                "margin": "0rem .65rem! important"
              }
            },
            ".nav-item: focus, .nav-link: focus": {
              "contour": "aucun"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3,8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem! important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "taille de la police 0,25 s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-boutons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".menu déroulant": {
              ".menu déroulant": {
                "background": "@menuBgColor",
                "display": "aucun",
                "position": "absolue",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0,235em 1,5385em 0,235em 1,5385em! important",
                  "&::après": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "& .open> .dropdown-menu": {
                "bloc de visualisation"
              }
            },
            ".navbar-toggleable-sm": {
              "& .opened: après": {
                "position": "absolue",
                "largeur": "100vw",
                "hauteur": "100vh",
                "contenu": "''",
                "background-color": "rgba (0, 0, 0, 0.1)",
                "gauche": "0",
                "bas": "0",
                "transform": "translateY (100%)",
                "-webkit-transform": "translateY (100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "tous les .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem! important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem! important"
                },
                "& img": {
                  "hauteur": "3rem! important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "hauteur": "18px",
              "curseur": "pointeur",
              "transition": "tous les .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:concentrer": {
                "contour": "aucun"
              },
              ".hamburger span": {
                "position": "absolue",
                "right": "0",
                "width": "30px",
                "hauteur": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&: nth-child (1)": {
                  "top": "0",
                  "transition": "tous les .2s"
                },
                "&: nth-child (2)": {
                  "top": "8px",
                  "transition": "tous les .15s"
                },
                "&: nth-child (3)": {
                  "top": "8px",
                  "transition": "tous les .15s"
                },
                "&: nth-child (4)": {
                  "top": "16px",
                  "transition": "tous les .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&: nth-child (1)": {
                "top": "8px",
                "largeur": "0",
                "opacity": "0",
                "droite": "50%",
                "transition": "tous les .2s"
              },
              "&: nth-child (2)": {
                "-webkit-transform": "rotate (45deg)",
                "transformer": "tourner (45deg)",
                "transition": "tous les .25s"
              },
              "&: nth-child (3)": {
                "-webkit-transform": "rotate (-45deg)",
                "transformer": "tourner (-45deg)",
                "transition": "tous les .25s"
              },
              "&: nth-child (4)": {
                "top": "8px",
                "largeur": "0",
                "opacity": "0",
                "droite": "50%",
                "transition": "tous les .2s"
              }
            },
            ".s'est effondré": {
              "& .navbar-expand": {
                "flex-direction": "colonne"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "aucun! important",
                "padding-right": "0! important",
                "& .collapsing, &. show": {
                  "display": "block! important",
                  ".navbar-nav": {
                    "bloc de visualisation",
                    "text-align": "center",
                    ".nav-item": {
                      "clarifier les deux",
                      "& quand (@showButtons = false)": {
                        "&:dernier enfant": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-boutons": {
                    "text-align": "center",
                    "&:dernier enfant": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "bloc de visualisation"
              },
              ".navbar-brand": {
                "margin-left": "1rem! important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "colonne",
                "-webkit-flex-direction": "colonne"
              },
              ".menu déroulant": {
                ".menu déroulant": {
                  "largeur": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "bloc de visualisation",
                  "hauteur": "0",
                  "visibilité": "caché",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "propriété de transition": "opacité, remplissage, hauteur"
                },
                "& .open> .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "hauteur": "auto",
                  "padding": "1.4rem 0",
                  "visibilité": "visible"
                },
                ".dropdown-submenu": {
                  "gauche": "0",
                  "text-align": "center",
                  "largeur": "100%"
                },
                ".dropdown-toggle [data-toggle = \" dropdown-submenu \ "] :: after": {
                  "margin-top": "0",
                  "position": "hériter",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "largeur": "0",
                  "hauteur": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "contenu": "\"\"",
                  "border-top": ".30em solide",
                  "border-right": ".30em solide transparent",
                  "border-left": ".30em solide transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              "& .navbar-expand": {
                "flex-direction": "colonne"
              },
              "img": {
                "height": "3.8rem! important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "bloc de visualisation"
              },
              ".navbar-brand": {
                "margin-left": "1rem! important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "colonne",
                "-webkit-flex-direction": "colonne"
              },
              ".navbar-collapse": {
                "display": "aucun! important",
                "padding-right": "0! important",
                "& .collapsing, &. show": {
                  "display": "block! important",
                  ".navbar-nav": {
                    "bloc de visualisation",
                    "text-align": "center",
                    ".nav-item": {
                      "clarifier les deux",
                      "& quand (@showButtons = false)": {
                        "&:dernier enfant": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-boutons": {
                    "text-align": "center",
                    "&:dernier enfant": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".menu déroulant": {
                ".menu déroulant": {
                  "largeur": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "bloc de visualisation",
                  "hauteur": "0",
                  "visibilité": "caché",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "propriété de transition": "opacité, remplissage, hauteur"
                },
                "& .open> .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "hauteur": "auto",
                  "padding": "1.4rem 0",
                  "visibilité": "visible"
                },
                ".dropdown-submenu": {
                  "gauche": "0",
                  "text-align": "center",
                  "largeur": "100%"
                },
                ".dropdown-toggle [data-toggle = \" dropdown-submenu \ "] :: after": {
                  "margin-top": "0",
                  "position": "hériter",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "largeur": "0",
                  "hauteur": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "contenu": "\"\"",
                  "border-top": ".30em solide",
                  "border-right": ".30em solide transparent",
                  "border-left": ".30em solide transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-base": "auto"
            },
            ".nav-link: hover, .dropdown-item: hover": {
              "color": "@itemsHoverColor! important"
            }
          },
          "_name": "menu2",
          "_customHTML": "<section class = \" menu \ "group = \" Menu \ "plugins = \" DropDown, TouchSwipe \ "toujours en haut global non-glissant une fois = \" menu \ "position-absolue> \ n \ n <mbr-parameters> \ n <! - Contrôle des paramètres de bloc (panneau bleu \ "Gear \") -> \ n <input type = \ "checkbox \" title = \ "Show Logo \" name = \ "showLogo \"> \ n <input type = \ "range \" title = \ "Logo Size \" inline name = \ "logoSize \" min = \ "3.8 \" max = \ "8 \" step = \ " 0.1 \ "value = \" 3.8 \ "condition = \" showLogo \ "> \ n <input type = \" checkbox \ "title = \" Show Brand Name \ "name = \" showBrand \ "> \ n <input type = \ "case à cocher \" title = \ "Afficher les éléments de menu \ "name = \" showItems \ "coché> \ n <input type = \" color \ "title = \" Items Hover Color \ "name = \" itemsHoverColor \ "value = \" # 767676 \ "condition = \ "showItems \"> \ n <input type = \ "checkbox \" title = \ "Afficher le (s) bouton (s) \" name = \ "showButtons \" coché> \ n <input type = \ "checkbox \" title = \ "Sticky \" name = \ "sticky \" coché> \ n <input type = \ "checkbox \" title = \ "Collapsed \" name = \ "collapsed \"> \ n <input type = \ "checkbox \ "title = \" Transparent \ "name = \" transparent \ "coché> \ n <input type = \" color \ "title = \" Hamburger Color \ "name = \" hamburgerColor \ "value = \" # 333333 \ "> \ n <input type = \ "color \" title = \ "Couleur d'arrière-plan \" name = \ "menuBgColor \" value = \ "# 65bf5c \"> \ n <! - Paramètres de bloc de fin -> \ n </mbr-parameters> \ n \ n <nav class = \ "navbar navbar-expand beta-menu navbar-dropdown align-items-center \" mbr-class = \ "{\ n 'navbar-fixed-top': sticky, \ n 'navbar-toggleable-sm':! collapsed, \ n 'collapsed': collapsed, \ n 'bg-color transparent': transparent \ n} \ "> \ n <button class = \" navbar-toggler navbar-toggler-right \ "type = \" button \ "data-toggle = \" collapse \ "data-target = \" # navbarSupportedContent \ "aria-controls = \" navbarSupportedContent \ "aria-extended = \" false \ "aria-label = \"Basculer la navigation \ "> \ n <div class = \" hamburger \ "> \ n <span> </span> \ n <span> </span> \ n <span> </span> \ n <span> < / span> \ n </div> \ n </button> \ n <div class = \ "menu-logo \"> \ n <div class = \ "navbar-brand \"> \ n <span mbr-if = \ "showLogo \" class = \ "navbar-logo \"> \ n <a href=\"https://mobirise.com\"> \ n <img src = \ "@ PROJECT_PATH @ / assets / images / mbr_0.jpg-122x81.jpg \ "alt = \" Mobirise \ "mbr-style = \" {'height': logoSize + 'rem'} \ "title> \ n </a> \ n </span>\ n <span mbr-if = \ "showBrand \" mbr-boutons mbr-theme-style = \ "display-4 \" class = \ "navbar-caption-wrap \" data-toolbar = \ "- mbrBtnMove, - mbrBtnAdd, -mbrBtnRemove \ "> \ n <a class = \" navbar-caption text-black \ "data-app-selector = \". navbar-caption \ "href = \" https: //mobirise.com \ " > \ n MOBIRISE \ n </a> \ n </span> \ n </div> \ n </div> \ n <div class = \ "collapse navbar-collapse \" id = \ "navbarSupportedContent \"> \ n <ul mbr-if = \ "showItems \" mbr-menu class = \ "navbar-nav nav-dropdown \" mbr-theme-style = \ "display-4 \" mbr-class = \ "{'nav -droite ':! showButtons, \ n'navbar-nav-top-padding ': isPublish &&! showBrand &&! showLogo} \ "> <li class = \" nav-item \ "> \ n <a class = \" nav-link link text-black \ "href = \ "https: //mobirise.com \" data-app-selector = \ ". nav-link, .dropdown-item \"> Accueil <br> Le projet <br> Les données & nbsp; <br> Nous contacter < / a> \ n </li> </ul> \ n <div mbr-if = \ "showButtons \" mbr-boutons mbr-theme-style = \ "display-4 \" class = \ "navbar-boutons mbr -section-btn \ "> <a class=\"btn btn-sm btn-primary\" href=\"tel:+1-234-567-8901\"> \ n <span class = \" btn-icon mbri-mobile mbr-iconfont mbr-iconfont-btn \ "data-app-selector = \". mbr-iconfont-btn \ ">\ n </span> </a> </div> \ n </div> \ n </nav> \ n </section> ",
          "_cid": "sclygbAaM4",
          "_anchor": "menu2-d",
          "_protectedParams": [],
          "_global": vrai,
          "_once": "menu",
          "_params": {}
        }
      ]
    },
    "page1.html": {
      "réglages": {
        "meta_descr": "Description de Web Page Maker",
        "title": "Le projet",
        "ordre": 1
      },
      "Composants": [
        {
          "_modes": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".counter-container": {
              "couleur": "# 767676",
              "ol": {
                "margin-bottom": "0",
                "li": {
                  "margin-bottom": "1rem"
                },
                "& quand (@stylizedCounters)": {
                  "counter-reset": "myCounter",
                  "li": {
                    "list-style": "aucun",
                    "padding-left": ".5rem",
                    "&:avant": {
                      "position": "absolue",
                      "gauche": "0px",
                      "margin-top": "-10px",
                      "counter-increment": "myCounter",
                      "content": "counter (myCounter)",
                      "display": "inline-block",
                      "text-align": "center",
                      "margin": "5px 10px",
                      "line-height": "40px",
                      "transition": "tous les .2s",
                      "couleur": "contraste (@counterColor)",
                      "background": "@counterColor",
                      "width": "40px",
                      "hauteur": "40px",
                      "border-radius": "50%",
                      "& quand (@squareCounters)": {
                        "border-radius": "0"
                      }
                    }
                  }
                }
              }
            },
            ".mbr-text": {
              "text-align": "left"
            },
            ".mbr-text LI": {
              "couleur": "# 232323"
            }
          },
          "_name": "content11",
          "_customHTML": "<section class = \" mbr-section article content11 \ "> \ n <mbr-parameters> \ n <! - Contrôles des paramètres de bloc (panneau bleu \" Gear \ ") -> \ n < input type = \ "range \" inline title = \ "Top \" name = \ "paddingTop \" min = \ "0 \" max = \ "8 \" step = \ "1 \" value = \ "4 \ "> \ n <input type = \" range \ "inline title = \" Bottom \ "name = \" paddingBottom \ "min = \" 0 \ "max = \" 8 \ "step = \" 1 \ "valeur = \ "4 \"> \ n <input type = \ "checkbox \" title = \ "Stylized Counters \" name = \ "stylizedCounters \" coché> \ n <input type = \ "checkbox \" title = \ " Compteurs carrés \ "name = \" squareCounters \ "condition = \ "stylizedCounters \"> \ n <input type = \ "color \" title = \ "Counter Color \" name = \ "counterColor \" value = \ "# 149dcc \" condition = \ "stylizedCounters \"> \ n <input type = \ "color \" title = \ "Couleur d'arrière-plan \" name = \ "bgColor \" value = \ "# ffffff \"> \ n <! - Paramètres de bloc de fin -> \ n < / mbr-parameters> \ n \ n <div class = \ "container \"> \ n <div class = \ "media-container-row \"> \ n <div class = \ "mbr-text counter-container col -12 col-md-8 mbr-fonts-style \ "mbr-theme-style = \" display-5 \ "data-app-selector = \". Mbr-text \ "data-multiline mbr-article> \ n <ol> \ n <li> <b> Le potager </b> </ li> \ n <li> L'aspect éducatif & nbsp; </li> <li> L'aspect <b>technologique </b> </li> \ n </ol> \ n </div> \ n </div> \ n </div> \ n </section> ",
          "_cid": "sclvF7wqwR",
          "_anchor": "content11-a",
          "_protectedParams": [],
          "_global": faux,
          "_once": faux,
          "_params": {}
        }
      ]
    }
  }
}
