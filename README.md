Year Calendar for Yii
=====================

This is a Yii extension based on my forked project of Arshaw fullcalendar.

This project adds a year view to the available views.


Install:

	Extract or clone the package in protected\extensions\yearcalendar


Example usage:

	<?php $this->widget('ext.yearcalendar.YearCalendar', array(
		'theme'=>'base',
		'options'=>array(
			'header'=>array(
				'left'=>'prev,next',
				'center'=>'title',
				'right'=>'year,month'
			),
			'theme'=>false,
			'defaultView'=>'year',
			'yearColumns'=>2,
		)));
	?>
