####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += ../common/util_pulse_gen.v
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += util_pulse_gen_ip.tcl

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.ip_user_files
M_FLIST += *.srcs
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil



.PHONY: all clean clean-all
all: util_pulse_gen.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


util_pulse_gen.xpr: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) util_pulse_gen_ip.tcl  >> util_pulse_gen_ip.log 2>&1

####################################################################################
####################################################################################
