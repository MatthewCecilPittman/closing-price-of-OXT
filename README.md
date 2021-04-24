# closing-price-of-OXT
using Pine Programming language in the pine editor on trading view 

// This source code is subject to the terms of the Mozilla Public License 2.0 at https://mozilla.org/MPL/2.0/
// © MatrixDivinity

//@version=4
study("price of ORCHID")
security("OXTUSD","D", close)
OXT_price = security("OXTUSD","D",close)
plot(OXT_price)
