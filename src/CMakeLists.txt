
#
# Main component of TF Micro project 'magic_wand'.
#

idf_component_register(
    SRCS main.cc main_functions.cc constants.cc magic_wand_model_data.cc accelerometer_handler.cc gesture_predictor.cc output_handler.cc
    INCLUDE_DIRS "")
