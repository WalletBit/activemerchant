Copyright (C) 2012 by Kris

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
	Bitcoin payment via walletbit.com for Active Merchant (Shopify & Spree).

Version 0.1
	Currency convert between all currencies automatically.

System Requirements:
	WalletBit.com account

Configuration Instructions:

	1. Add the following to your Gemfile, and run 'bundle install'
		gem 'walletbit', :git => 'https://github.com/walletbit/activemerchant.git'

	2. In WalletBit.com IPN URL https://walletbit.com/businesstools/IPN Enter this link http://YOUR_ECOMMERCE_URL/callback/
	3. Enter a strong Security Word in WalletBit IPN.
	4. In module settings "E-Mail" <- set your WalletBit.com email.
	5. In module settings "Token" <- copy from WalletBit.com https://walletbit.com/businesstools/IPN "Token"
	6. In module settings "Security Word" <- Enter the Security Word you created in step 3.