####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += ../common/ad_iqcor.v
M_DEPS += ../common/up_axi.v
M_DEPS += ../common/up_xfer_cntrl.v
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += axi_adc_decimate.v
M_DEPS += axi_adc_decimate_constr.xdc
M_DEPS += axi_adc_decimate_filter.v
M_DEPS += axi_adc_decimate_ip.tcl
M_DEPS += axi_adc_decimate_reg.v
M_DEPS += cic_decim.v
M_DEPS += fir_decim.v

M_DEPS += ../util_cic/util_cic.xpr

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



.PHONY: all dep clean clean-all
all: dep axi_adc_decimate.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


axi_adc_decimate.xpr: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) axi_adc_decimate_ip.tcl  >> axi_adc_decimate_ip.log 2>&1

dep:
	$(MAKE) -C ../util_cic/
####################################################################################
####################################################################################
