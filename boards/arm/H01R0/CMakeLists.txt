# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20.0)
set(BOARD_ROOT F:/Zephyr/boards)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(H01R0_app)

# target_sources(app PRIVATE src/main.c)
