# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_QCOM_TSENS)	+= qcom_tsens.o
qcom_tsens-y			+= tsens.o tsens-v2.o tsens-v1.o tsens-v0_1.o \
					tsens-8960.o
obj-$(CONFIG_QCOM_SPMI_ADC_TM5)	+= qcom-spmi-adc-tm5.o
obj-$(CONFIG_QCOM_SPMI_MBG_TM)	+= qcom-spmi-mbg-tm.o
obj-$(CONFIG_QCOM_SPMI_TEMP_ALARM)	+= qcom-spmi-temp-alarm.o
obj-$(CONFIG_QCOM_LMH)		+= lmh.o
obj-$(CONFIG_QTI_CPU_PAUSE_COOLING_DEVICE) += thermal_pause.o
obj-$(CONFIG_QTI_BCL_PMIC5) += bcl_pmic5.o
obj-$(CONFIG_QTI_BCL_SOC_DRIVER) += bcl_soc.o
obj-$(CONFIG_QTI_CPU_HOTPLUG_COOLING_DEVICE) += cpu_hotplug.o
obj-$(CONFIG_QTI_CPU_VOLTAGE_COOLING_DEVICE) += cpu_voltage_cooling.o
obj-$(CONFIG_QTI_DDR_COOLING_DEVICE) += ddr_cdev.o
obj-$(CONFIG_MAX31760_FAN_CONTROLLER) += max31760_fan.o
obj-$(CONFIG_QTI_THERMAL_LIMITS_DCVS) += msm_lmh_dcvs.o
obj-$(CONFIG_QTI_POLICY_ENGINE_SENSOR) += policy_engine.o

obj-$(CONFIG_QTI_QMI_COOLING_DEVICE) += qti_qmi_cdev.o
qti_qmi_cdev-y += thermal_mitigation_device_service_v01.o qmi_cooling.o

obj-$(CONFIG_QTI_QMI_SENSOR_V2) += qti_qmi_sensor_v2.o
qti_qmi_sensor_v2-y += thermal_sensor_service_v02.o qmi_sensors_v2.o

obj-$(CONFIG_QTI_CPUFREQ_CDEV) += qti_cpufreq_cdev.o
obj-$(CONFIG_QTI_DEVFREQ_CDEV) += qti_devfreq_cdev.o
obj-$(CONFIG_QTI_USERSPACE_CDEV) += qti_userspace_cdev.o
obj-${CONFIG_QTI_SDPM_CLOCK_MONITOR} += sdpm_clk.o
obj-$(CONFIG_QTI_THERMALZONE_CONFIG_DEBUG) += thermal_config.o
obj-$(CONFIG_THERMAL_TSENS_LEGACY)	+= msm-tsens-driver.o
msm-tsens-driver-y			+= msm-tsens.o tsens2xxx.o tsens-dbg.o tsens-calib.o tsens-mtc.o tsens1xxx.o
obj-$(CONFIG_QTI_LMH_CPU_VDD_COOLING_DEVICE) += lmh_cpu_vdd_cdev.o
obj-$(CONFIG_QTI_CX_IPEAK_COOLING_DEVICE) += cx_ipeak_cdev.o
obj-$(CONFIG_REGULATOR_COOLING_DEVICE) += regulator_cdev.o
obj-$(CONFIG_QTI_QMI_SENSOR) += qti_qmi_sensor.o
qti_qmi_sensor-y += thermal_sensor_service_v01.o qmi_sensors.o
obj-$(CONFIG_QTI_RPM_SMD_COOLING_DEVICE) += rpm_smd_cooling_device.o
obj-$(CONFIG_QTI_THERMAL_MINIDUMP) += thermal_minidump.o
obj-$(CONFIG_QTI_BCL_OFF_COOLING_DEVICE) += bcl_off_cdev.o
obj-$(CONFIG_QTI_VIRTUAL_SENSOR) += virtual-sensor.o
obj-$(CONFIG_QTI_AOP_PMIC_SENSOR) += qti_aop_pmic_sensor.o
