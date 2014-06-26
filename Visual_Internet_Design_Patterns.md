Visual Internet Design Patterns
===============================


1. ## VI (Visual Internet) Definition 
The Visual Internet is not necessarily new internet technology but rather using the existing web technology with a well-defined accent on multiple provider cooperation in order to achieve a total visual immersion of the end user in a 2D or 3D or in a combination of 2D and 3D virtual space.

	This document identifies some common VI design patterns in terms of software depelopment, present-day technology for implementation, UI design, recommendations for API for deep linking and provider cooperation. It clearly identifies usecases, classes of viewers and the possible embeddings.
	
	This document will be further detailed as demand for further details are needed for a wider audience and will be maintained and updated also following demand.

* ## VI Characteristics
VI differs from the present Web that is mostly HTML web pages by a series of of properties and their derivatives:

	1. deep or total immersion
		1. viewer is used full-screen
		* optimization for VR navigation
		* reduced need for keyboard as input
		* navigation from one provider to the next is seamless (no need to know the URL)
		* the user should have all needed data in the same space and with natural, intuitive navigation
		* common theming for multiple providers
	* predilection for vectorial space data
		1. SVG instead of raster images



* ## VI and the Semantic Web
 ### VI as consumer of the SW data ###
VI will initially be used as consumer of the SW. The SW will provide nevigational means to VI by means of automated connectivity, indexing, organization of presentation. See 2D ontology usecase and Metainterface navigational control
	
* ##VI in 2D
	
	* ### 1. Recommended Usecases
	For now this takes the form of a list of fields of use: 
		* text
		* formated text
		* terrestrial/surface maps
		* microscopy
		* 2D graphs
		* diagrams
		* shapes
		* icons
		* ideograms
		* photography
		* video
		* atlas plates
		* tomography/radiology
		* electronic circuits
		* floor plans
		* DNA maps
		* simple charts
	* ### 2. Components
	* ### 3. Software Design
	* ### 4. UI Patterns
	* ### 5. Specific Viewer Control
	* ### 6. Specific API
* ## VI in 3D
	* ### Recommended Usecases
	For now this takes the form of a list of fields of use:  
		* anatomical structures
		* astronomy
		* 3D models
		* CAD
		* architecture
		* mechanical structures
		* brain maps
		* gene activation maps
		* topographic maps
		* deep marine/underground maps
	* ### 2. Components
	* ### 3. Software Design
	* ### 4. UI Patterns
	* ### 5. Specific Viewer Control
	* ### 6. Specific API
* ## Data Entry
	* keyboard, parametrized keyboard
	* mouse
	* touch devices
	* gyroscope
	* head position (AR and VR)
* ## Interconnection and API for automatic consumption
	* Absolute and relative units
	* Controlled vocabulary interchange
	* Theme interchange
	* Language interchange
	* Embedding rules: partial hashing of URLs
	* Data distribution on update, insert, delete
* ## Formatting for printing and exact resolution ratios
	* Printing to paper ratio
* ## Metainterface and navigation control
	* by semantics
		* ontology
		* tag intersection
	* by dimensional neighborhood
		* discrete
		* continuous
* ## Principles of collaboration
	* The viewer should be:
		* loaded at the entry point
		* the same at all entry points (eventually loaded from a common repo)
		* themeable
	* The long text eventually exchanged should be in Markdown format or produced by [html2text](https://github.com/html2text/html2text). This way the text is easy to parse by controlled vocabulary recognizers
* ## List of present providers and points of entry
	* ![Sapiens Mapping Project](http://sliced.ro/smp/nav2d.php)
	* ![Sapiens Education Project](http://thesapiens.ro)
