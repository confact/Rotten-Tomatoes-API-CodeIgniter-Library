Rotten-Tomatoes-API-CodeIgniter-Library
=======================================
Rotten Tomatoes Movie Database API CodeIgniter Library

contributors
======================================
created by by Jake Monton - <montonjake89@gmail.com>
forked and made even better by Håkan Nylén (Confact) <hakan@dun.se>

/**
 * Rotten tomatoes v1.0 
 * PHP class - wrapper to Rotten Tomatoes v1.0 API
 * API Documentation - http://developer.rottentomatoes.com/docs
 * 
 * @author ekaj_03 <montonjake89@gmail.com>, confact <hakan@dun.se>
 * @copyright 2012 ekaj_03
 * @date 2012-09-11
 * @link https://github.com/ekaj03/Rotten-Tomatoes-API-CodeIgniter-Library
 * @version 0.0.1
 * 
 */

/**
 * Drop the RottenTomatoes.php file to your libraries folder.
 * Drop the rotten_config.php file to your config folder.
 * Drop the rotten.php file to your controllers folder. 
 */

/** Sample way of using the Rotten Tomatoes API CodeIgniter Library
 * Set your config in rotten_config.
 * // load RottenTomatoes library
 * $this->load->library('RottenTomatoes', 'rotten');
 * $movie_from = 'in_theaters';  // in_theaters, box_office, opening, upcoming 
 * $page_limit = 45;
 * $page = 1;
 * $movies = $this->rotten->getMovies($movie_from, $page_limit, $page);  

