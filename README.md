# KAP.TABS 

Kap.tabs is nothing more but simple tabs. No powerful configuration, no powerful features.

__BUT__

## Features

- Module weights only __1.47 kB__. Perfect.
(Yeah, npm may show you more, but it's cause of README. Don't look at that)
- If you don't need such a hard tabs, you can use and don't give a damn about the downloading page

## Installation

    npm i kap-tabs


__Nothing more__

## Usage


    import tabs from 'tabs';
    tabs(tabsSelector, contentSelector, parentSelector, activeClass);

## Configuration

| Parameter     |    Meaning    |
| ------------- | ------------- |
| `tabsSelector`  | Selector, which defines on what do you click to change tabs |
| `contentSelector`  | Selector, which defines where located content of each tab  |
| `parentSelector`  | Selector of parent element  |
| `activeClass`  | Certain __CLASS__, which defines the active tab |

## WARNING

Your CSS files must contain next classes:

- __show__ <br>
For example:

        show{
            opacity: 1;
            display: block;
            visibility: visible;
        }

- __hide__ <br>
For example:

        hide{
            opacity: 0;
            display: none;
            visability: hidden;
        }

- __fade__ (Not necessary) <br>
For example:

        .fade{
            animation-name: fade;
            animation-duration: 1.5s;
        }
        @keyframes fade{
            from{
                opacity: 0.1;
            }
            to{
                opacity: 1;
            }
        }



## Support

- Make pull requests in case of suggestions: https://github.com/kapiernik/kap-tabs
- Write on my email: kapiernik27@gmail.com

## License

The project is licensed under the MIT license.
