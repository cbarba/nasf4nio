# Makefile
#
# (C) 2018 Carlos M. Fonseca <cmfonsec@dei.uc.pt>
# 
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3 of the License, or (at
# your option) any later version.
# 
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software Foundation,
# Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

.PHONY: all clean debug

all:
	@$(MAKE) -C solver
	@$(MAKE) -C nqueens
	@$(MAKE) -C flowshop
	@$(MAKE) -C knapsack

clean:
	@$(MAKE) -C solver clean
	@$(MAKE) -C nqueens clean
	@$(MAKE) -C flowshop clean
	@$(MAKE) -C knapsack clean
	rm -f *~ core include/*~

debug:
	@$(MAKE) -C solver debug
	@$(MAKE) -C nqueens debug
	@$(MAKE) -C flowshop debug
	@$(MAKE) -C knapsack debug


