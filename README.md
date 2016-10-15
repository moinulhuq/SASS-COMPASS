# SASS-COMPASS
Syntactically Awesome Style Sheets

project file structure pattern

https://sass-guidelin.es/#the-7-1-pattern

base/
	_reset.scss
	_typography.scss
	_color.scss

components/
	_buttons.scss
	_navigation.scss
	_gallery.scss
	_carousel.scss
	_cover.scss
	_dropdown.scss
	_thumbnails.scss

layout/
	_header.scss
	_footer.scss
	_grid.scss
	_sidebar.scss
	_forms.scss

pages/
	_home.scss
	_about.scss
	_contact.scss

themes/
	_theme.scss
	_admin.scss

helpers/ (or utils/) / abstracts
	_variables.scss
	_functions.scss
	_mixins.scss
	_placeholders.scss

vendors/
	_bootstrap.scss
	_jquery-ui.scss

_attach.scss
		@import 'base/_typography.scss';
		@import 'base/_color.scss';

		/*
		@import 'abstracts/_functions.scss';
		@import 'abstracts/_mixins.scss';
		@import 'abstracts/_placeholders.scss';
		@import 'abstracts/_variables.scss';
		*/

		@import 'components/_buttons.scss';
		@import 'components/_cover.scss';
		@import 'components/_dropdown.scss';
		@import 'components/_navigation.scss';
		@import 'components/_thumbnails.scss';

		@import 'layout/_footer.scss';
		@import 'layout/_forms.scss';
		@import 'layout/_header.scss';
		@import 'layout/_sidebar.scss';
