{% from "common/macros.njk" import embed_topic, show_admin_sections_to_read, show_as_tab, thumb, timing_badge with context %}
{% from "common/admin.njk" import policies, show_admin_summary, topics with context %}

{% call show_admin_summary() %}
1. Enhance previous week's increment or add another individual feature
1. Start preparing for the final submission
{% endcall %}

<span id="week12-project">

#### {{ thumb(1) }} Enhance previous week's feature

* If you chose option 1 in the previous week, you can either continue to enhance the GUI or add an individual feature this week (from the three choices from option 2).
* If you chose option 2 in the previous week, you can either continue to enhance that individual feature or add another individual feature from the three choices given to you.


#### {{ thumb(2) }} Start preparing for the final submission

* ==Note that you can get prof's feedback for your project report before the final submission==. See the panel below for more details.

{{ embed_topic("../../admin/index-tee3201-fragment.md#final-submission-info", "Admin " + icon_embedding + " Project → Final Submission", "1", indent="2") }}

</span>
