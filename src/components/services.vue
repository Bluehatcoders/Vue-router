
<template>
    <div id="appCapsule">
       
       
        <!-- Wallet Card -->
        <div class="section wallet-card-section pt-1">
            <div class="wallet-card" id="1234bap">
                <!-- Balance -->
                <div class="balance" style="margin-bottom: 0px !important;">
                    <div class="left">
                        <div class="l-wrapper u-pr--16 u-pl--16 u-pt--32" id="list"></div>
                    </div><div class="right">
                        
                           <svg data-toggle="modal" style="cursor: pointer;" data-target="#depositActionSheet" width="56" height="56" viewBox="0 0 64 64" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns="http://www.w3.org/2000/svg" xmlns:cc="http://creativecommons.org/ns#" xmlns:dc="http://purl.org/dc/elements/1.1/" version="1.1">
						<g transform="translate(0.00630876,-0.00301984)">
							<path fill="#f7931a" d="m63.033,39.744c-4.274,17.143-21.637,27.576-38.782,23.301-17.138-4.274-27.571-21.638-23.295-38.78,4.272-17.145,21.635-27.579,38.775-23.305,17.144,4.274,27.576,21.64,23.302,38.784z"></path>
							<path fill="#FFF" d="m46.103,27.444c0.637-4.258-2.605-6.547-7.038-8.074l1.438-5.768-3.511-0.875-1.4,5.616c-0.923-0.23-1.871-0.447-2.813-0.662l1.41-5.653-3.509-0.875-1.439,5.766c-0.764-0.174-1.514-0.346-2.242-0.527l0.004-0.018-4.842-1.209-0.934,3.75s2.605,0.597,2.55,0.634c1.422,0.355,1.679,1.296,1.636,2.042l-1.638,6.571c0.098,0.025,0.225,0.061,0.365,0.117-0.117-0.029-0.242-0.061-0.371-0.092l-2.296,9.205c-0.174,0.432-0.615,1.08-1.609,0.834,0.035,0.051-2.552-0.637-2.552-0.637l-1.743,4.019,4.569,1.139c0.85,0.213,1.683,0.436,2.503,0.646l-1.453,5.834,3.507,0.875,1.439-5.772c0.958,0.26,1.888,0.5,2.798,0.726l-1.434,5.745,3.511,0.875,1.453-5.823c5.987,1.133,10.489,0.676,12.384-4.739,1.527-4.36-0.076-6.875-3.226-8.515,2.294-0.529,4.022-2.038,4.483-5.155zm-8.022,11.249c-1.085,4.36-8.426,2.003-10.806,1.412l1.928-7.729c2.38,0.594,10.012,1.77,8.878,6.317zm1.086-11.312c-0.99,3.966-7.1,1.951-9.082,1.457l1.748-7.01c1.982,0.494,8.365,1.416,7.334,5.553z"></path>
						</g>
					</svg>
                      
                    </div>
                   
                    
                </div>
                <!-- * Balance -->
                <!-- Wallet Footer -->
               
                <!-- * Wallet Footer -->
            </div>
        </div>
        <!-- Wallet Card -->

        <!-- Deposit Action Sheet -->
        <div class="modal fade modalbox" id="depositActionSheet" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Bitcoin </h5>
                        <a href="javascript:;" data-dismiss="modal">Close</a>
                    </div>
                    <div class="modal-body" style="padding: 0px !important;">
                        <div class="section mt-2" id="list1" style="padding: 0 1px !important; margin-top: 0px !important;">
                        </div>
                         
                    </div>
                </div>
            </div>
        </div>
     <div class="modal fade modalbox panelbox-right" id="ModalBasic" tabindex="-1" role="dialog" style="display: none;" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    
<div class="appHeader bg-primary">
        <div class="left">
            <a href="#" class="headerButton goBack" data-dismiss="modal" style="
    color: #fff;
">
                <ion-icon name="chevron-back-outline" role="img" class="md hydrated" aria-label="chevron back outline"></ion-icon>
            </a>
        </div>
        <div class="pageTitle">
            Notifications
        </div>
        <div class="right">
            
        </div>
    </div>
<div class="section full">

            <ul class="listview image-listview flush">
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-primary">
                            <ion-icon name="arrow-down-outline" role="img" class="md hydrated" aria-label="arrow down outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Payment Received</strong></div>
                                <div class="text-small mb-05">John sent you <b>$ 50</b></div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                            <span class="badge badge-primary badge-empty"></span>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-success">
                            <ion-icon name="arrow-forward-outline" role="img" class="md hydrated" aria-label="arrow forward outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Money has been sent</strong></div>
                                <div class="text-small mb-05">The money you sent to John was successfully sent.</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                            <span class="badge badge-primary">3</span>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-danger">
                            <ion-icon name="key-outline" role="img" class="md hydrated" aria-label="key outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Password changed</strong></div>
                                <div class="text-small mb-05">Your password has been changed</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-warning">
                            <ion-icon name="chatbubble-outline" role="img" class="md hydrated" aria-label="chatbubble outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>New Messages</strong></div>
                                <div class="text-small mb-05">You have new messages from John</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-primary">
                            <ion-icon name="arrow-down-outline" role="img" class="md hydrated" aria-label="arrow down outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Payment Received</strong></div>
                                <div class="text-small mb-05">John sent you <b>$ 50</b></div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-success">
                            <ion-icon name="arrow-forward-outline" role="img" class="md hydrated" aria-label="arrow forward outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Money has been sent</strong></div>
                                <div class="text-small mb-05">The money you sent to John was successfully sent.</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-danger">
                            <ion-icon name="key-outline" role="img" class="md hydrated" aria-label="key outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>Password changed</strong></div>
                                <div class="text-small mb-05">Your password has been changed</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="app-notification-detail.html" class="item">
                        <div class="icon-box bg-warning">
                            <ion-icon name="chatbubble-outline" role="img" class="md hydrated" aria-label="chatbubble outline"></ion-icon>
                        </div>
                        <div class="in">
                            <div>
                                <div class="mb-05"><strong>New Messages</strong></div>
                                <div class="text-small mb-05">You have new messages from John</div>
                                <div class="text-xsmall">5/3/2020 10:30 AM</div>
                            </div>
                        </div>
                    </a>
                </li>
            </ul>

        </div>
                    
                </div>
            </div>
        </div>
        <!-- Withdraw Action Sheet -->
        <div class="modal fade action-sheet" id="withdrawActionSheet" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Withdraw</h5>
                    </div>
                    <div class="modal-body">
                        <div class="action-sheet-content">
                            <form>
                                <div class="form-group basic">
                                    <div class="input-wrapper">
                                        <label class="label" for="account2d">From</label>
                                        <select class="form-control custom-select" id="account2d">
                                            <option value="0">Savings (*** 5019)</option>
                                            <option value="1">Investment (*** 6212)</option>
                                            <option value="2">Mortgage (*** 5021)</option>
                                        </select>
                                    </div>
                                </div>

                                <div class="form-group basic">
                                    <div class="input-wrapper">
                                        <label class="label" for="text11d">To</label>
                                        <input type="email" class="form-control" id="text11d" placeholder="Enter IBAN">
                                        <i class="clear-input">
                                            <ion-icon name="close-circle"></ion-icon>
                                        </i>
                                    </div>
                                </div>

                                <div class="form-group basic">
                                    <label class="label">Enter Amount</label>
                                    <div class="input-group mb-2">
                                        <div class="input-group-prepend">
                                            <span class="input-group-text" id="input14d">$</span>
                                        </div>
                                        <input type="text" class="form-control form-control-lg" placeholder="0">
                                    </div>
                                </div>

                                <div class="form-group basic">
                                    <button type="button" class="btn btn-primary btn-block btn-lg"
                                        data-dismiss="modal">Send</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- * Withdraw Action Sheet -->

        <!-- Send Action Sheet -->
        <div class="modal fade action-sheet" id="technical-analysis" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Technical Analysis</h5>
                    </div>
                    <div class="modal-body" style="height: 400px;">
                    <iframe id="settings" style="height: 435px;"src="https://s.tradingview.com/embed-widget/technical-analysis/?locale=in#%7B%22interval%22%3A%221m%22%2C%22width%22%3A425%2C%22isTransparent%22%3Afalse%2C%22height%22%3A450%2C%22symbol%22%3A%22BITFINEX%3ABTCINR%22%2C%22showIntervalTabs%22%3Atrue%2C%22colorTheme%22%3A%22light%22%2C%22utm_source%22%3A%22in.tradingview.com%22%2C%22utm_medium%22%3A%22widget_new%22%2C%22utm_campaign%22%3A%22technical-analysis%22%7D"></iframe>
                    </div>
                </div>
            </div>
        </div>

        <div class="modal fade action-sheet" id="technical-analysiseth" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Technical Analysis</h5>
                    </div>
                    <div class="modal-body" style="height: 400px;">
                    <iframe id="settings" style="height: 435px;"src="https://s.tradingview.com/embed-widget/technical-analysis/?locale=in#%7B%22interval%22%3A%221m%22%2C%22width%22%3A425%2C%22isTransparent%22%3Afalse%2C%22height%22%3A450%2C%22symbol%22%3A%22BITFINEX%3AETHINR%22%2C%22showIntervalTabs%22%3Atrue%2C%22colorTheme%22%3A%22light%22%2C%22utm_source%22%3A%22in.tradingview.com%22%2C%22utm_medium%22%3A%22widget_new%22%2C%22utm_campaign%22%3A%22technical-analysis%22%7D"></iframe>
                    </div>
                </div>
            </div>
        </div>

        <div class="modal fade action-sheet" id="technical-analysisltc" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Technical Analysis</h5>
                    </div>
                    <div class="modal-body" style="height: 400px;">
                    <iframe id="settings" style="height: 435px;"src="https://s.tradingview.com/embed-widget/technical-analysis/?locale=in#%7B%22interval%22%3A%221m%22%2C%22width%22%3A425%2C%22isTransparent%22%3Afalse%2C%22height%22%3A450%2C%22symbol%22%3A%22BITFINEX%3ALTCINR%22%2C%22showIntervalTabs%22%3Atrue%2C%22colorTheme%22%3A%22light%22%2C%22utm_source%22%3A%22in.tradingview.com%22%2C%22utm_medium%22%3A%22widget_new%22%2C%22utm_campaign%22%3A%22technical-analysis%22%7D"></iframe>
                    </div>
                </div>
            </div>
        </div>

        <div class="modal fade action-sheet" id="technical-analysisxpr" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Technical Analysis</h5>
                    </div>
                    <div class="modal-body" style="height: 400px;">
                    <iframe id="settings" style="height: 435px;"src='https://s.tradingview.com/embed-widget/technical-analysis/?locale=in#%7B"interval"%3A"1m"%2C"width"%3A425%2C"isTransparent"%3Afalse%2C"height"%3A450%2C"symbol"%3A"XRPINR"%2C"showIntervalTabs"%3Atrue%2C"colorTheme"%3A"light"%2C"utm_source"%3A"in.tradingview.com"%2C"utm_medium"%3A"widget_new"%2C"utm_campaign"%3A"technical-analysis"%7D'></iframe>
                    </div>
                </div>
            </div>
        </div>

        <div class="modal fade action-sheet" id="technical-analysisusdt" tabindex="-1" role="dialog">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Technical Analysis</h5>
                    </div>
                    <div class="modal-body" style="height: 400px;">
                    <iframe id="settings" style="height: 435px;"src='https://s.tradingview.com/embed-widget/technical-analysis/?locale=in#%7B%22interval%22%3A%221m%22%2C%22width%22%3A425%2C%22isTransparent%22%3Afalse%2C%22height%22%3A450%2C%22symbol%22%3A%22KRAKEN%3AUSDTUSD%22%2C%22showIntervalTabs%22%3Atrue%2C%22colorTheme%22%3A%22light%22%2C%22utm_source%22%3A%22in.tradingview.com%22%2C%22utm_medium%22%3A%22widget_new%22%2C%22utm_campaign%22%3A%22technical-analysis%22%7D'></iframe>
                    </div>
                </div>
            </div>
        </div>
        <!-- * Send Action Sheet -->

      <div class="modal fade action-sheet" id="exchangeActionSheet" tabindex="-1" role="dialog" style="display: none;" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title">Convert Currency</h5>
                    </div>
                    <div class="modal-body">
                        <iframe id="settings" style="height: 330px;" src="https://widget.coinlib.io/widget?type=converter&amp;theme=light"></iframe>
                    </div>
                </div>
            </div>
        </div>
        <!-- Stats -->
        

        <div class="section mt-3">
            
            <div class="card">
                <div class="card-body">
                    <ul class="nav nav-tabs style1" role="tablist">
                        <li class="nav-item">
                            <a class="nav-link active" data-toggle="tab" href="#overview" role="tab" aria-selected="true">Trending
</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" data-toggle="tab" href="#card" role="tab" aria-selected="false">Losers</a>
                        </li>
                        
                    </ul>
                    <div class="tab-content mt-1">
                        <div class="tab-pane fade active show" id="overview" role="tabpanel"><table class="table rounded"><thead>
			<tr>
                                <th scope="col">Currency</th>
                                <th scope="col">Last 7 Days</th>
                                
                                <th scope="col" class="text-right"> Price&nbsp;&nbsp;</th>
                            </tr>
		</thead><tbody>
    <tr class="">
			<th scope="row">Ethereum</th>
            <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/279/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value1">----</td>
            </tr><tr class=""><th scope="row">Litecoin</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/2/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value3">----</td>
            </tr><tr class=""><th scope="row">Sora</th> 
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/11093/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value2">----</td>
            </tr><tr class=""> <th scope="row">Gnosis</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/662/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value4">----</td>
            </tr><tr class=""><th scope="row">Aave</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/12645/sparkline" style="width: 94px;height: 43px;"></td> 
                                <td class="text-right text-primary" id="value5">----</td>
            </tr><tr class=""><th scope="row">Dash</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/19/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value6">----</td>
            </tr><tr class=""><th scope="row">Monero</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/69/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value7">----</td>
            </tr><tr class=""><th scope="row">sETH</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/8843/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value9">----</td>
            </tr><tr class=""><th scope="row">Maker</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/1364/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value8">----</td>
            </tr><tr class=""><th scope="row">Kusama</th>
                <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/9568/sparkline" style="width: 94px;height: 43px;"></td>
                                <td class="text-right text-primary" id="value10">----</td>
                            
			</tr>
    </tbody></table></div>
                        <div class="tab-pane fade" id="card" role="tabpanel">
                            <table class="table rounded"><thead>
                                <tr>
                                                    <th scope="col">Currency</th>
                                                    <th scope="col">Last 7 Days</th>
                                                    
                                                    <th scope="col" class="text-right"> Price</th>
                                                </tr>
                            </thead><tbody>
                        <tr class="">
<th scope="row">Tether</th>
<td style="padding: 0px;"><img src="https://www.coingecko.com/coins/325/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value11">----</td>
</tr><tr class=""><th scope="row">Uniswap</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/12504/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value12">----</td>
</tr><tr class=""><th scope="row">Dai</th> 
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/9956/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value13">----</td>
</tr><tr class=""> <th scope="row">Sushi</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/12271/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value14">----</td>
</tr><tr class=""><th scope="row">Ampleforth</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/4708/sparkline" style="width: 94px;height: 43px;"></td> 
                    <td class="text-right text-primary" id="value15">----</td>
</tr><tr class=""><th scope="row">FunFair</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/761/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value16">----</td>
</tr><tr class=""><th scope="row">Vitae</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/5504/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value17">----</td>
</tr><tr class=""><th scope="row">Tokenlon</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/13454/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value18">----</td>
</tr><tr class=""><th scope="row">Edgeware</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/8452/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value19">----</td>
</tr><tr class=""><th scope="row">Unibright</th>
    <td style="padding: 0px;"><img src="https://www.coingecko.com/coins/2707/sparkline" style="width: 94px;height: 43px;"></td>
                    <td class="text-right text-primary" id="value20">----</td>
                
</tr>
    </tbody></table>
    </div>
    <div class="tab-pane fade" id="settings" role="tabpanel">
                            Vestibulum sed facilisis diam, vel sodales leo. Aenean lacinia, nisi sit amet iaculis
                            maximus, nibh orci iaculis risus, vitae faucibus dui orci quis elit.
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- * Stats -->

        <!-- Transactions -->
        <div class="section mt-4">
            <div class="section-heading">
                <h2 class="title">Market Cap</h2>
                <a href="app-transactions.html" class="link">View All</a>
            </div>
            <div class="transactions">
                <!-- item -->
                <a href="#" class="item" data-toggle="modal" data-target="#technical-analysis">
                    <div class="detail">
                        <img src="https://s3.us-east-2.amazonaws.com/nomics-api/static/images/currencies/btc.svg" alt="img" class="image-block imaged w48">
                        <div>
                            <strong>Bitcoin</strong>
                            <p>Tap for Technical Analysis</p>
                        </div>
                    </div>
                    <div class="right">
                        <div class="price" id="btcpre"></div>
                    </div>
                </a>
                <!-- * item -->
                <!-- item --> 
                     <a href="#" class="item" data-toggle="modal" data-target="#technical-analysiseth">
                    <div class="detail">
                        <img src="https://s3.us-east-2.amazonaws.com/nomics-api/static/images/currencies/eth.svg" style="height: 48px;" alt="img" class="image-block imaged w48">
                        <div>
                            <strong>Ethereum</strong>
                            <p>Tap for Technical Analysis</p>
                        </div>
                    </div>
                    <div class="right">
                        <div class="price" id="ethpre"></div>
                    </div>
                </a>
             
                <!-- * item -->
                <!-- item -->
                <a href="#" class="item" data-toggle="modal" data-target="#technical-analysisxpr">
                    <div class="detail">
                        <img src="https://s3.us-east-2.amazonaws.com/nomics-api/static/images/currencies/XPR.png" alt="img" class="image-block imaged w48">
                        <div>
                            <strong>Ripple</strong>
                            <p>Tap for Technical Analysis</p>
                        </div>
                    </div>
                    <div class="right">
                        <div class="price" id="xrppre"></div>
                    </div>
                </a>
                 <!-- * item -->
                <!-- item -->
                <a href="#" class="item" data-toggle="modal" data-target="#technical-analysisusdt">
                    <div class="detail">
                        <img src="https://s3.us-east-2.amazonaws.com/nomics-api/static/images/currencies/usdt.svg" alt="img" class="image-block imaged w48">
                        <div>
                            <strong>Tether</strong>
                            <p>Tap for Technical Analysis</p>
                        </div>
                    </div>
                    <div class="right">
                        <div class="price" id="usdtpre"></div>
                    </div>
                </merahai>
                <!-- * item -->
                <!-- item -->
                <a href="#" class="item" data-toggle="modal" data-target="#technical-analysisltc">
                    <div class="detail">
                        <img src="https://s3.us-east-2.amazonaws.com/nomics-api/static/images/currencies/ltc.svg" alt="img" class="image-block imaged w48">
                        <div>
                            <strong>Litecoin</strong>
                            <p>Tap for Technical Analysis</p>
                        </div>
                    </div>
                    <div class="right">
                        <div class="price" id="ltcpre"></div>
                    </div>
                </a>
                <!-- * item -->
            </div>
        </div>
        <!-- * Transactions -->

        

        <!-- Send Money -->
        <div class="section full mt-4">
            <div class="section-heading padding">
                <h2 class="title">Send Money</h2>
                <a href="javascript:;" class="link">Add New</a>
            </div>
            <div class="shadowfix carousel-small owl-carousel owl-theme">
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar2.jpg" alt="img" class="imaged w-48">
                            <strong>Jurrien</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar3.jpg" alt="img" class="imaged w-48">
                            <strong>Elwin</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar4.jpg" alt="img" class="imaged w-48">
                            <strong>Alma</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar5.jpg" alt="img" class="imaged w-48">
                            <strong>Justine</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar6.jpg" alt="img" class="imaged w-48">
                            <strong>Maria</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar7.jpg" alt="img" class="imaged w-48">
                            <strong>Pamela</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar8.jpg" alt="img" class="imaged w-48">
                            <strong>Neville</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar9.jpg" alt="img" class="imaged w-48">
                            <strong>Alex</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <a href="#">
                        <div class="user-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/avatar/avatar10.jpg" alt="img" class="imaged w-48">
                            <strong>Stina</strong>
                        </div>
                    </a>
                </div>
                <!-- * item -->
            </div>
        </div>
        <!-- * Send Money -->

        <!-- Monthly Bills -->
        <div class="section full mt-4">
            <div class="section-heading padding">
                <h2 class="title">Monthly Bills</h2>
                <a href="app-bills.html" class="link">View All</a>
            </div>
            <div class="carousel-multiple owl-carousel owl-theme shadowfix">
                <!-- item -->
                <div class="item">
                    <div class="bill-box">
                        <div class="img-wrapper">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/brand/1.jpg" alt="img" class="image-block imaged w48">
                        </div>
                        <div class="price">$ 14</div>
                        <p>Prime Monthly Subscription</p>
                        <a href="#" class="btn btn-primary btn-block btn-sm">PAY NOW</a>
                    </div>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <div class="bill-box">
                        <div class="img-wrapper">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/brand/2.jpg" alt="img" class="image-block imaged w48">
                        </div>
                        <div class="price">$ 9</div>
                        <p>Music Monthly Subscription</p>
                        <a href="#" class="btn btn-primary btn-block btn-sm">PAY NOW</a>
                    </div>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <div class="bill-box">
                        <div class="img-wrapper">
                            <div class="iconbox bg-danger">
                                <ion-icon name="medkit-outline"></ion-icon>
                            </div>
                        </div>
                        <div class="price">$ 299</div>
                        <p>Monthly Health Insurance</p>
                        <a href="#" class="btn btn-primary btn-block btn-sm">PAY NOW</a>
                    </div>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <div class="bill-box">
                        <div class="img-wrapper">
                            <div class="iconbox">
                                <ion-icon name="card-outline"></ion-icon>
                            </div>
                        </div>
                        <div class="price">$ 962</div>
                        <p>Credit Card Statement
                        </p>
                        <a href="#" class="btn btn-primary btn-block btn-sm">PAY NOW</a>
                    </div>
                </div>
                <!-- * item -->
            </div>
        </div>
        <!-- * Monthly Bills -->


        <!-- Saving Goals -->
        <div class="section mt-4">
            <div class="section-heading">
                <h2 class="title">Saving Goals</h2>
                <a href="app-savings.html" class="link">View All</a>
            </div>
            <div class="goals">
                <!-- item -->
                <div class="item">
                    <div class="in">
                        <div>
                            <h4>Gaming Console</h4>
                            <p>Gaming</p>
                        </div>
                        <div class="price">$ 499</div>
                    </div>
                    <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 85%;" aria-valuenow="85"
                            aria-valuemin="0" aria-valuemax="100">85%</div>
                    </div>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <div class="in">
                        <div>
                            <h4>New House</h4>
                            <p>Living</p>
                        </div>
                        <div class="price">$ 100,000</div>
                    </div>
                    <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 55%;" aria-valuenow="55"
                            aria-valuemin="0" aria-valuemax="100">55%</div>
                    </div>
                </div>
                <!-- * item -->
                <!-- item -->
                <div class="item">
                    <div class="in">
                        <div>
                            <h4>Sport Car</h4>
                            <p>Lifestyle</p>
                        </div>
                        <div class="price">$ 42,500</div>
                    </div>
                    <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 15%;" aria-valuenow="15"
                            aria-valuemin="0" aria-valuemax="100">15%</div>
                    </div>
                </div>
                <!-- * item -->
            </div>
        </div>
        <!-- * Saving Goals -->


        <!-- News -->
        <div class="section full mt-4 mb-3">
            <div class="section-heading padding">
                <h2 class="title">Lastest News</h2>
                <a href="app-blog.html" class="link">View All</a>
            </div>
            <div class="shadowfix carousel-multiple owl-carousel owl-theme owl-loaded owl-drag">

                <!-- item -->
                
                <!-- * item -->

                <!-- item -->
                
                <!-- * item -->

                <!-- item -->
                
                <!-- * item -->

                <!-- item -->
                
                <!-- * item -->

            <div class="owl-stage-outer"><div class="owl-stage" style="transition: all 0.25s ease 0s; width: 1468px; padding-left: 32px; padding-right: 32px; transform: translate3d(-526px, 0px, 0px);"><div class="owl-item cloned" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/3.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">10 easy ways to save your money</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item cloned" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/4.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">Follow the financial agenda with...</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/1.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">What will be the value of bitcoin in the next...</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item active" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/2.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">Rules you need to know in business</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item active" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/3.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">10 easy ways to save your money</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/4.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">Follow the financial agenda with...</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item cloned" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/1.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">What will be the value of bitcoin in the next...</h4>
                            </div>
                        </div>
                    </a>
                </div></div><div class="owl-item cloned" style="width: 159.5px; margin-right: 16px;"><div class="item">
                    <a href="app-blog-post.html">
                        <div class="blog-card">
                            <img src="https://finapp.bragherstudio.com/view2/assets/img/sample/photo/2.jpg" alt="image" class="imaged w-100">
                            <div class="text">
                                <h4 class="title">Rules you need to know in business</h4>
                            </div>
                        </div>
                    </a>
                </div></div></div></div><div class="owl-nav disabled"><button type="button" role="presentation" class="owl-prev"><span aria-label="Previous">‹</span></button><button type="button" role="presentation" class="owl-next"><span aria-label="Next">›</span></button></div><div class="owl-dots disabled"></div></div>
        </div>
        <!-- * News -->


        <!-- app footer -->
        <div class="appFooter" id="li" style="display: none;">
            <div class="footer-title">
                Copyright © Finapp 2020. All Rights Reserved.
            </div>
            Bootstrap 4 based mobile template.
        </div>
        <!-- * app footer -->

    </div>
    <!-- * App Capsule -->
   
</template>
<script>
	export default{
		name:'blog',
		data (){
			return{
				title:'services'
			}
		}
	}
</script>

<style scoped>
	
</style>
