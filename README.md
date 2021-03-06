# ServiceNow

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license-shield]][license-url]

## About The Project

In this project you will find some of my scripts, update sets, cheatsheets, and whatever related to ServiceNow I may find interesting at some point.

### Scripts

| Name | Description | Application | Scope |
| -- | -- | -- | -- |
| [`find_user_node.js`](./scripts/find_user_node.js) | Returns the node which a user is logged-in to | Platform | Global |
| [`find_events_claimed_by_ghost_node.js`](./scripts/find_events_claimed_by_ghost_node.js) | Returns events claimed by nodes which are not running in the instance anymore | Platform | Global |
| [`ppm_fix_user_duplicated_capacity.js`](./scripts/ppm_fix_user_duplicated_capacity.js) | Fix/print resource users with duplicated records in aggregate tables | PPM | Global |

### Other

| Name | Description |
| -- | -- |
| [`doc.py`](./other/doc.py) | Utility for parsing update sets (`update_set.xml`) and create a Markdown file containing information abput the update set and the manual actions |
| [`text_formatter.js`](./other/text_formatter.js) | Save as a browser bookmark, enhance the *Additional Comments* field including format |

### Docs

* [MID Server Troubleshooting](./docs/mid_server_troubleshooting.md)
* [How to attach a file to a mail by script](./docs/attach_file_mail.md)
* [ServiceNow UI Developer Cheatsheet](./docs/ui_cheatsheet.md)
* [Opened for / Subject person](.docs/opened_for_subject_person.md)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## License

See `LICENSE` for more information.

## Contact

* [alexalvarez.es](https://www.alexalvarez.es)

* [alexalvarez@mail.com](mailto:alexalvarez@mail.com)

[contributors-shield]: https://img.shields.io/github/contributors/AlexAlvarez092/servicenow.svg?style=for-the-badge
[contributors-url]: https://github.com/AlexAlvarez092/servicenow/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/AlexAlvarez092/servicenow.svg?style=for-the-badge
[forks-url]: https://github.com/AlexAlvarez092/servicenow/network/members

[stars-shield]: https://img.shields.io/github/stars/AlexAlvarez092/servicenow.svg?style=for-the-badge
[stars-url]: https://github.com/gAlexAlvarez092/servicenow/stargazers

[issues-shield]: https://img.shields.io/github/issues/AlexAlvarez092/servicenow.svg?style=for-the-badge
[issues-url]: https://github.com/AlexAlvarez092/servicenow/issues

[license-shield]: https://img.shields.io/github/license/AlexAlvarez092/servicenow.svg?style=for-the-badge
[license-url]: https://github.com/AlexAlvarez092/servicenow/blob/master/LICENSE.txt
