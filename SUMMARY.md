# Summary

* [OpenTX 2.1 Lua Reference Guide](README.md)
* [Introduction](introduction.md)
   * [Acknowledgments](acknowledgments.md)
   * [Getting Started](getting_started.md)
* [Part I - Script Type Overview](part_i_-_script_type_overview.md)
   * [Mix Scripts](mix.md)
   * [Telemetry Scripts](telemetry.md)
   * [One-Time Scripts](one-time_scripts.md)
   * [Wizard Script](wizard.md)
   * [Function Scripts](function_scripts.md)
* [Part II - OpenTX Lua API Programming Guide](part_ii_-_opentx_lua_api_programming_guide.md)
   * [Input Table Syntax](input_table_syntax.md)
   * [Output Table Syntax](output_table_syntax.md)
   * [Init Function Syntax](init_function_syntax.md)
   * [Run Function Syntax](run_function_syntax.md)
   * [Return Statement Syntax](return_statement_syntax.md)
   * [Included Lua Libraries](included_lua_libraries.md)
* [Part III - OpenTX Lua API Reference](part_iii_-_opentx_lua_api_reference.md)
   * [Constants](constants.md)
       * [Key Event Constants](key_events.md)
   * [General Functions](general_functions.md)
       * [getTime()](gettime.md)
       * [getDateTime()](getdatetime.md)
       * [getVersion()](getversion.md)
       * [getGeneralSettings()](getgeneralsettings.md)
       * [getValue()](getvalue_function.md)
       * [getFieldInfo()](getfieldinfo_function.md)
       * [playFile()](playfile.md)
       * [playNumber()](playnumber.md)
       * [playDuration()](playduration.md)
       * [playTone()](playtone.md)
       * [popupInput()](popupinput.md)
       * [defaultStick()](defaultstick.md)
       * [defaultChannel()](defaultchannel.md)
       * [killEvents()](killevents.md)
       * [GREY()](grey.md)
   * [Model Functions](model_functions.md)
       * [model.getInfo()](modelgetinfo.md)
       * [model.setInfo()](modelsetinfo.md)
       * [model.getModule()](modelgetmodule.md)
       * [model.setModule()](modelsetmodule.md)
       * [module.getTimer()](modulegettimer.md)
       * [model.setTimer()](modelsettimer.md)
       * [model.resetTimer()](modelresettimer.md)
       * [model.getInputsCount()](modelgetinputscount.md)
       * [model.getInput()](modelgetinput.md)
       * [model.insertInput()](modelinsertinput.md)
       * [model.deleteInput()](modeldeleteinput.md)
       * [model.deleteInputs()](modeldeleteinputs.md)
       * [model.getMixesCount()](modelgetmixescount.md)
       * [model.getMix()](modelgetmix.md)
       * [model.insertMix()](modelinsertmix.md)
       * [model.deleteMix()](modeldeletemix.md)
       * [model.deleteMixes()](modeldeletemixes.md)
       * [model.getLogicalSwitch()](modelgetlogicalswitch.md)
       * [model.setLogicalSwitch()](modelsetlogicalswitch.md)
       * [model.getCustomFunction()](modelgetcustomfunction.md)
       * [model.setCustomFunction()](modelsetcustomfunction.md)
       * [model.getCurve()](modelgetcurve.md)
       * [model.getOutput()](modelgetoutput.md)
       * [model.setOutput()](modelsetoutput.md)
       * [model.getGlobalVariable()](modelgetglobalvariable.md)
       * [model.setGlobalVariable()](modelsetglobalvariable.md)
   * [Display Functions](display_functions.md)
       * [ldc.lock()](ldclock.md)
       * [lcd.clear()](lcdclear.md)
       * [lcd.getLastPos()](lcdgetlastpos.md)
       * [lcd.drawPoint()](lcddrawpoint.md)
       * [lcd.drawLine()](lcddrawline.md)
       * [lcd.drawRectangle()](lcddrawrectangle.md)
       * [lcd.drawFilledRectangle()](lcddrawfilledrectangle.md)
       * [lcd.drawGauge()](lcddrawgauge.md)
       * [lcd.drawText()](lcddrawtext.md)
       * [lcd.drawTimer()](lcddrawtimer.md)
       * [lcd.drawNumber()](lcddrawnumber.md)
       * [lcd.drawChannel()](lcddrawchannel.md)
       * [lcd.drawSwitch()](lcddrawswitch.md)
       * [lcd.drawSource()](lcddrawsource.md)
       * [lcd.drawPixmap()](lcddrawpixmap.md)
       * [lcd.drawScreenTitle()](lcddrawscreentitle.md)
       * [lcd.drawCombobox()](lcddrawcombobox.md)
* [Part IV - Converting OpenTX 2.0 Scripts](part_iv_-_converting_opentx_20_scripts.md)
   * [General Issues](known_issues.md)
   * [Handling GPS Sensor data](handling_gps_sensor_data.md)
   * [Handling Lipo Sensor Data](handling_lipo_sensor_data.md)

