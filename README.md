# PHP-FPM and Nginx Docker Image for WordPress.

WordPress container with Nginx and PHP-FPM 7 based on Alpine Linux.
_WordPress version currently installed:_ **4.8** 
	
	* You can easy update wordpress version if you want by changing it into docker compose file
	* This config is doesn't include anything that we don't absolutely need in the runtime.

## Usage 

	You need To rename the docker-compose{version}.yml file that you want to docker-compose.yml


| Compose file format | Docker Engine version |

| --- | --- |
| 3.0 | 1.13.0+ |
| 2.0 | 1.10.0+ |
	
	Run docker-compose up, wait for it to initialize completely, and visit http://localhost