.. _api:


#############
API Reference
#############

Plot creation
=============
.. currentmodule:: plotnine
.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: members-example.rst

   ggplot
   qplot
   aes
   ~layer.layer
   ~layer.Layers


geoms
=====
.. currentmodule:: plotnine.geoms

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   geom_abline
   geom_area
   geom_bar
   geom_blank
   geom_boxplot
   geom_col
   geom_count
   geom_crossbar
   geom_density
   geom_dotplot
   geom_errorbar
   geom_errorbarh
   geom_freqpoly
   geom_bin2d
   geom_histogram
   geom_hline
   geom_jitter
   geom_label
   geom_line
   geom_linerange
   geom_path
   geom_point
   geom_pointrange
   geom_polygon
   geom_quantile
   geom_qq
   geom_rect
   geom_ribbon
   geom_rug
   geom_segment
   geom_smooth
   geom_spoke
   geom_step
   geom_text
   geom_tile
   geom_violin
   geom_vline


Related to geoms
----------------

.. autosummary::
   :toctree: generated/
   :template: main.rst

   annotate
   arrow


Labels
------
.. currentmodule:: plotnine.labels

.. autosummary::
   :toctree: generated/
   :template: main.rst

   labs
   xlab
   ylab
   ggtitle


stats
=====
.. currentmodule:: plotnine.stats

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   stat_bin
   stat_bin_2d
   stat_bindot
   stat_boxplot
   stat_count
   stat_density
   stat_ecdf
   stat_function
   stat_identity
   stat_qq
   stat_quantile
   stat_smooth
   stat_sum
   stat_summary
   stat_summary_bin
   stat_unique
   stat_ydensity


facets
======
.. currentmodule:: plotnine.facets

.. autosummary::
   :toctree: generated/
   :template: main.rst

   facet_grid
   facet_null
   facet_wrap
   ~labelling.labeller
   ~labelling.as_labeller
   ~labelling.label_value
   ~labelling.label_both
   ~labelling.label_context


scales
======
.. currentmodule:: plotnine.scales


Base scales
-----------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   ~scale.scale
   ~scale.scale_discrete
   ~scale.scale_continuous


Alpha scales
------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_alpha
   scale_alpha_discrete
   scale_alpha_continuous


Identity Scales
---------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_alpha_identity
   scale_color_identity
   scale_colour_identity
   scale_fill_identity
   scale_linetype_identity
   scale_shape_identity
   scale_size_identity


Color and fill scales
---------------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_color_brewer
   scale_color_cmap
   scale_color_continuous
   scale_color_desaturate
   scale_color_discrete
   scale_color_distiller
   scale_color_gradient
   scale_color_gradient2
   scale_color_gradientn
   scale_color_gray
   scale_color_grey
   scale_color_hue
   scale_fill_brewer
   scale_fill_cmap
   scale_fill_continuous
   scale_fill_desaturate
   scale_fill_discrete
   scale_fill_distiller
   scale_fill_gradient
   scale_fill_gradient2
   scale_fill_gradientn
   scale_fill_gray
   scale_fill_grey
   scale_fill_hue


Manual scales
-------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_alpha_manual
   scale_color_manual
   scale_colour_manual
   scale_fill_manual
   scale_linetype_manual
   scale_shape_manual
   scale_size_manual


Linetype scales
---------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_linetype
   scale_linetype_discrete


Shape scales
------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_shape
   scale_shape_discrete


Size scales
-----------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_size
   scale_size_area
   scale_size_continuous
   scale_size_discrete
   scale_size_radius


Position scales
---------------
.. autosummary::
   :toctree: generated/
   :template: main.rst

   scale_x_continuous
   scale_x_date
   scale_x_datetime
   scale_x_discrete
   scale_x_log10
   scale_x_reverse
   scale_x_sqrt
   scale_x_timedelta
   scale_y_continuous
   scale_y_date
   scale_y_datetime
   scale_y_discrete
   scale_y_log10
   scale_y_reverse
   scale_y_sqrt
   scale_y_timedelta


Scale limits
------------
.. currentmodule:: plotnine.scales

.. autosummary::
   :toctree: generated/
   :template: main.rst

   lims
   xlim
   ylim
   expand_limits


Scale guides
------------
.. currentmodule:: plotnine.guides

.. autosummary::
   :toctree: generated/
   :template: main.rst

   guides
   ~guide.guide
   guide_legend
   guide_colorbar


positions
=========
.. currentmodule:: plotnine.positions

.. autosummary::
   :toctree: generated/
   :template: main.rst

   position_dodge
   position_fill
   position_identity
   position_jitter
   position_jitterdodge
   position_nudge
   position_stack


themes
======

.. currentmodule:: plotnine.themes

.. autosummary::
   :toctree: generated/
   :template: main.rst

   theme
   theme_538
   theme_bw
   theme_classic
   theme_dark
   theme_gray
   theme_grey
   theme_light
   theme_linedraw
   theme_matplotlib
   theme_minimal
   theme_seaborn
   theme_void
   theme_xkcd


Themeables
----------

These define aspects of a plot that can be themed. They
can be used to create a new theme or modify an existing theme.
They define the keyword arguments to :class:`~plotnine.themes.theme`.
Users should never create instances of *themeable*.

.. currentmodule:: plotnine.themes.themeable

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: themeables.rst

   aspect_ratio
   axis_line
   axis_line_x
   axis_line_y
   axis_text
   axis_text_x
   axis_text_y
   axis_ticks
   axis_ticks_direction
   axis_ticks_direction_x
   axis_ticks_direction_y
   axis_ticks_length
   axis_ticks_length_major
   axis_ticks_length_minor
   axis_ticks_major
   axis_ticks_major_x
   axis_ticks_major_y
   axis_ticks_minor
   axis_ticks_minor_x
   axis_ticks_minor_y
   axis_ticks_pad
   axis_ticks_pad_major
   axis_ticks_pad_minor
   axis_title
   axis_title_x
   axis_title_y
   dpi
   figure_size
   legend_background
   legend_box
   legend_box_background
   legend_box_just
   legend_box_margin
   legend_box_spacing
   legend_direction
   legend_entry_spacing
   legend_entry_spacing_x
   legend_entry_spacing_y
   legend_key
   legend_key_height
   legend_key_size
   legend_key_width
   legend_margin
   legend_position
   legend_spacing
   legend_text
   legend_text_colorbar
   legend_text_legend
   legend_title
   legend_title_align
   line
   panel_background
   panel_border
   panel_grid
   panel_grid_major
   panel_grid_major_x
   panel_grid_major_y
   panel_grid_minor
   panel_grid_minor_x
   panel_grid_minor_y
   panel_ontop
   panel_spacing
   panel_spacing_x
   panel_spacing_y
   plot_background
   plot_margin
   plot_title
   rect
   strip_background
   strip_background_x
   strip_background_y
   strip_margin
   strip_margin_x
   strip_margin_y
   strip_text
   strip_text_x
   strip_text_y
   subplots_adjust
   text
   title
   themeable


Theme helper functions and classes
----------------------------------

.. currentmodule:: plotnine.themes

.. autosummary::
   :toctree: generated/
   :template: main.rst

   theme_set
   theme_get
   theme_update
   element_line
   element_rect
   element_text


coordinates
===========

.. currentmodule:: plotnine.coords

.. autosummary::
   :toctree: generated/
   :template: main.rst

   coord_cartesian
   coord_equal
   coord_fixed
   coord_flip
   coord_trans


options
=======

When working interactively, some of the options make it convenient to
create plots that have a common look and feel. Another way to do it,
to set a default theme using :func:`~plotnine.themes.theme_set`.

.. currentmodule:: plotnine.options

.. autosummary::
   :toctree: generated/
   :template: main.rst

   aspect_ratio
   close_all_figures
   current_theme
   dpi
   figure_size
   get_option
   set_option


datasets
========

.. currentmodule:: plotnine.data

.. autosummary::
   :toctree: generated/
   :template: data.rst

   diamonds
   economics
   economics_long
   faithfuld
   huron
   luv_colours
   meat
   midwest
   mpg
   msleep
   mtcars
   pageviews
   presidential
   seals
   txhousing
