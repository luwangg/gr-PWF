# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.
install(FILES
    PWF_sigmagen.xml
    PWF_pilot_gen.xml
    PWF_pilot_gen_tx.xml
    PWF_pilot_gen_rx.xml
    PWF_channel.xml
    PWF_pilot_receive.xml
    PWF_pilot_receive_tx.xml
    PWF_pilot_receive_tx_sync.xml
    PWF_pilot_receive_rx.xml
    PWF_pilot_receive_rx_sync.xml
    PWF_power_adjust.xml
    PWF_weighted_sum_rate.xml
    PWF_debug_printmsg.xml
    PWF_identity_sum_rate.xml
    PWF_channel.xml
    PWF_rx_frame_sync.xml
    PWF_ML_frame_sync.xml
    PWF_weighted_sum_rate_usrp.xml
    PWF_pilot_receive_usrp.xml DESTINATION share/gnuradio/grc/blocks
)
