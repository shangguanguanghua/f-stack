# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2018 NXP

if not is_linux
	build = false
	reason = 'only supported on linux'
endif

deps += ['bus_fslmc']
sources = files('dpaa2_hw_mempool.c')

# depends on fslmc bus which uses experimental API
allow_experimental_apis = true
