Arshaw's Full Calendar
======================

Great JavaScript calendar as Yii extension.

Install:

	Extract or clone the package in protected\extensions\efullcalendar


Example usage:

	<?php $this->widget('ext.efullcalendar.EFullCalendar', array(
		'theme'=>'base',
		'options'=>array(
			'header'=>array(
				'left'=>'prev,next',
				'center'=>'title',
				'right'=>'today'
			)
		)));
    ?>
