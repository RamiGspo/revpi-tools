# SPDX-License-Identifier: GPL-2.0-or-later
#
# SPDX-FileCopyrightText: 2024 KUNBUS GmbH

set(copy_files
	Kyuafile
	resize_fs_test
	test_env.sh
)

foreach(file IN LISTS copy_files)
	configure_file(${file} ${file} COPYONLY)
endforeach()
