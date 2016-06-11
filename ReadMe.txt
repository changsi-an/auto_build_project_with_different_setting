This example demostrate a way to automatically build the same project multiple times, with different settings. So you don't have to duplicate or share the source code assets in different projects and keep only the single source of truth.

A practical use is to build the same C++ library project into both DLL and LIB.

The following comes from the origin Win32 DLL project template.
========================================================================
    DYNAMIC LINK LIBRARY : rebuild_with_different_config Project Overview
========================================================================

AppWizard has created this rebuild_with_different_config DLL for you.

This file contains a summary of what you will find in each of the files that
make up your rebuild_with_different_config application.


rebuild_with_different_config.vcxproj
    This is the main project file for VC++ projects generated using an Application Wizard.
    It contains information about the version of Visual C++ that generated the file, and
    information about the platforms, configurations, and project features selected with the
    Application Wizard.

rebuild_with_different_config.vcxproj.filters
    This is the filters file for VC++ projects generated using an Application Wizard. 
    It contains information about the association between the files in your project 
    and the filters. This association is used in the IDE to show grouping of files with
    similar extensions under a specific node (for e.g. ".cpp" files are associated with the
    "Source Files" filter).

rebuild_with_different_config.cpp
    This is the main DLL source file.

	When created, this DLL does not export any symbols. As a result, it
	will not produce a .lib file when it is built. If you wish this project
	to be a project dependency of some other project, you will either need to
	add code to export some symbols from the DLL so that an export library
	will be produced, or you can set the Ignore Input Library property to Yes
	on the General propert page of the Linker folder in the project's Property
	Pages dialog box.

/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named rebuild_with_different_config.pch and a precompiled types file named StdAfx.obj.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" comments to indicate parts of the source code you
should add to or customize.

/////////////////////////////////////////////////////////////////////////////
