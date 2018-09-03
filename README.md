# MyFristRepository
第一次用github


用css的过渡做的一个简单的小动画
 <?xml version="1.0" encoding="UTF-8"?>
<policies  name=’cscf_scale_in‘ zh-desc="kpi_trigger" version="v3.0">
    <policy name="CPU_Scaling" zh-desc="cpu_load_monitor" version="v3.0">
        <condition name="CPU_Load_PL" desc="metrics" direction="negative">13</condition>
        <action name="PL_scale" desc="">scalein</action>
</policy>
</policies>
