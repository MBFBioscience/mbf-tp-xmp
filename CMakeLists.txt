# =================================================================================================
# ADOBE SYSTEMS INCORPORATED
# Copyright 2013 Adobe Systems Incorporated
# All Rights Reserved
#
# NOTICE: Adobe permits you to use, modify, and distribute this file in accordance with the terms
# of the Adobe license agreement accompanying it.
# =================================================================================================

# ==============================================================================
# define minimum cmake version
if(ANDROID)
	cmake_minimum_required(VERSION 3.5.2...3.5.2)
else(ANDROID)
	cmake_minimum_required(VERSION 3.15.5...3.28.1)
endif(ANDROID)

# project
project(XMPToolkitSDK)

# continue to build cmake file
add_subdirectory(build)
