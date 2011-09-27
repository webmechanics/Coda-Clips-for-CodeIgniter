# Collection of Coda Clips for CodeIgniter development

Contents:

### Create components

* Create controller
* Create model

### Load components

* Load model
* Load view
* Load helper
* Load library
* Load language file

### Variables

* POST variable
* SESSION variable
* URI segment
* Language string

### Misc

* PHP placeholder
* Enable CI profiler
* PHP print placeholder

### Load model (load model [tab])

	$this->load->model('*');

### Load view (load view [tab])

	$this->load->view('*', $data, TRUE);

### Load helper (load helper [tab])

	$this->load->helper('*');

### Load library (load library [tab])

	$this->load->library('*');
	
### Load language file (load lang [tab])

	$this->load->language('*');

### Insert SESSION variable (ci_session [tab])

	$this->session->userdata('*')

### Insert URI segment variable (ci_uri [tab])

	$this->uri->segment(*)

### Insert POST variable (ci_post [tab])

	$this->input->post('*')

### Insert GET variable (ci_get [tab])

	$this->input->get('*')
	
### Insert language string (lang [tab])

	<?= lang('*'); ?>

### Create model skeleton (make model [tab])

	<?php

	class My_model extends CI_Model {

		function __construct(){
			parent::__construct();
		}

		*
	}

### Create controller skeleton (make controller [tab])

	<?php

	class My_controller extends CI_Controller {

		function __construct() {
	
			parent::__construct();
		}
	
		function index() {
	
			*
		}
	}

### PHP construction placeholder (php [tab])

	<?php * ?>

### PHP print placeholder (php= [tab])

	<?= * ?>

### Enable CI profiler (ci_debug [tab])

	$this->output->enable_profiler(TRUE);

### FirePHP debug call (fire [tab])

	// FirePHP Debug Start

	$this->firephp->fb();
