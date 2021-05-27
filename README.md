# fordiscord
/**
 * @name Materialistic
 * @author BigMeanie
 * @version 1.0.0
 * @description A clean material design theme for discord with a simple accent color
 * @invite P9fAbrDjQ6
*/

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap');

/*Credits to Gibbu for making the original adjustable server width and radial status themes*/
@import url('https://gibbu.github.io/BetterDiscord-Themes/AdjustableServerWidth/base.css');
@import url('https://gibbu.github.io/BetterDiscord-Themes/RadialStatus/base.css');


body,
button,
input,
select,
textarea,
::placeholder,
::-moz-placeholder,
:-ms-input-placeholder {
  font-family: var(--main-font)!important;
}

.name-1jkAdW,
.tierTooltipTitle-3AtaZT,
.markup-2BOw-j,
.modeUnread-1qO3K1 .name-23GUGE,
.topSectionNormal-2-vo2m .username-3gJmXY,
.guildNick-3uAm3i,
.listName-3w10cx,
.connectedAccountName-f8AEe2,
.errorState-KkUH_2,
.defaultColor-1_ajX0,
.header-1-dBpZ,
.username-31C1TQ,
.lookLink-9FtZy-.colorPrimary-3b3xI6,
.colorStandard-2KCXvj,
.match-38WbBN,
.uploadModal-2ifh8j .inner-3nWsbo,
.name-uJV0GL {
  color: var(--text-color);
}

.cozy-3raOZG .timestamp-3ZCmNB,
.cozy-3raOZG .timestamp-3ZCmNB.alt-1uNpEt {
  color: var(--text-color-dark);
}

.selected-3s45Ha.item-PXvHYJ,
.selected-3s45Ha.item-PXvHYJ:hover,
.connectedAccountOpenIcon-2cNbq5:hover,
.button-1ZiXG9:hover .icon-3Gkjwa,
.button-38aScr:hover .buttonWrapper-1ZmCpA,
.clickable-3rdHwn .icon-22AiRD:hover,
.colorBrand-ROmMP1,
.icon-2yIBmh,
.button-1w5pas,
.icon-2yIBmh:hover,
.icon-22AiRD,
.strikethrough-3Wiitd,
.disableColor-2z9rkr,
.modeSelected-346R90 .name-23GUGE,
.modeSelected-346R90 .actionIcon-PgcMM2,
.modeSelected-346R90 .icon-1DeIlz,
.edited-3sfAzf,
.strikethrough-1n4ekb,
.closeIcon-2Yg8TD,
.closeIcon-2Yg8TD:hover,
.icon-1S6UIr,
.icon-3cZ1F_,
.navButton-2gQCx-,
.side-8zPYf6 .header-2RyJ0Y,
.fieldTitle-3h2iLW.h5-18_1nd,
.menu-319q29,
.defaultValue-3gC7yw .markValue-2DwdXI,
.topSectionNormal-2-vo2m .additionalActionsIcon-1FoUlE:hover,
.button-14-BFJ.enabled-2cQ-u7:hover,
.winButton-iRh8-Z,
.close-hZ94c6,
.close-hZ94c6:hover,
.search-1iTphC .searchBox-2_mAlO .searchIcon-6ljH-4,
.avatar-3uk_u9,
.colorDefault-2K3EoJ .checkbox-3s5GYZ,
.colorDefault-2K3EoJ .check-1JyqgN:hover,
.closeIcon-2eaC4U,
.addButtonIcon-2CbG1X:hover,
.added-2hLRj3,
.improved-1NJK-y,
.fixed-3zCC84,
.content-s2SEQO a,
.keybindShortcut-1BD6Z1,
.warning-3C2pOH .icon-1jlFSw,
.dots-3Bkt3k.themed-IQiCm3,
.resultsGroup-r_nuzN .searchLearnMore-3SQUAj svg,
.resultsGroup-r_nuzN .searchClearHistory-2cSSMO svg,
.topSectionNormal-2-vo2m .discriminator-xUhQkU {
  color: var(--accent-color-main);
}

.mentioned-xhSam7::before,
.item-2hkk8m,
.unread-2lAfLh,
.barButtonIcon-3t4V3d,
.iconBadge-qZ4Ksk,
.newMessagesBar-265mhP,
.unreadPill-2HyYtt,
.mention-1f5kbO,
.modeSelected-346R90 .content-1x5b-n:hover,
.containerDefault--pIXnN:hover,
.categoryItem-1QIroW:hover,
.added-2hLRj3:after,
.improved-1NJK-y:after,
.fixed-3zCC84:after,
.bd-settings-group.collapsible .bd-settings-title::after,
.checkbox-1ix_J3.checked-3_4uQ9 svg {
  background-color: var(--accent-color-main);
}

.numberBadge-2s8kKX,
.liveSmall-1dy2uA,
.header-2-Imhb .tabBar-1kuXvJ .tab-ck0077.active-1MbGPa,
.side-8zPYf6 .themed-OHr7kt:hover,
.lookFilled-1Gx00P.colorGrey-2DXtkV:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled:hover,
.item-3HknzM.themed-OHr7kt[aria-controls="ADD_FRIEND-tab"]:hover,
.item-PXvHYJ.themed-OHr7kt[aria-controls="Discord Nitro-tab"]:hover,
.item-PXvHYJ.themed-OHr7kt[aria-selected="true"][aria-controls="Discord Nitro-tab"],
.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover {
  color: var(--accent-color-dark)!important;
  background-color: var(--accent-color-main)!important;
}

.lookFilled-1Gx00P.colorGrey-2DXtkV,
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled {
  color: var(--accent-color-main)!important;
  background-color: var(--accent-color-dark)!important;
}

.warning-3C2pOH {
  background: var(--accent-color-dark);
  border: 1px solid var(--accent-color-main);
  color: var(--text-color);
}

.barButtonBase-2uLO1z,
.unreadPill-2HyYtt,
.channel-2QD9_O:hover .linkButtonIcon-Mlm5d6,
.channel-2QD9_O:hover .name-uJV0GL,
.channel-2QD9_O:hover .subText-1KtqkB,
.isUnread-3Ef-o9 .content-1o0f9g,
.icon-1ihkOt,
.bar-30k2ka,
.modeSelected-346R90:hover .icon-1DeIlz,
.modeSelected-346R90:hover .name-23GUGE,
.modeSelected-346R90:hover .actionIcon-PgcMM2,
.containerDefault--pIXnN:hover .icon-1DeIlz,
.containerDefault--pIXnN:hover .name-23GUGE,
.containerDefault--pIXnN:hover .actionIcon-PgcMM2,
.clickable-3rdHwn .icon-22AiRD:hover .strikethrough-3Wiitd,
.layout-2DM8Md:hover .avatar-3uk_u9,
.layout-2DM8Md:hover .name-uJV0GL,
.colorDefault-2K3EoJ .check-1JyqgN,
.item-1tOPte:hover .colorDefault-2K3EoJ .checkbox-3s5GYZ,
.searchOption-zQ-1l6:hover .filter-3Y_im-,
.option-96V44q:hover .filter-3Y_im-,
.searchOption-zQ-1l6:hover .answer-1n6g43,
.option-96V44q:hover .answer-1n6g43,
.option-96V44q:hover .nonText-3CRkO {
  color: var(--accent-color-dark);
}

.container-3auIfb rect,
.closeButton-1tv5uR path,
.bd-switch-slider rect,
.base-gE7OpD .slowModeIcon-1BPDC_ path .button-38aScr:hover .attachButtonPlus-jWVFah,
.bd-select-arrow,
.bd-server-search svg,
.typeWindows-1za-n7>.wordmark-2iDDfm>svg>path {
  fill: var(--accent-color-main);
}

.container-3auIfb path,
.checkbox-1ix_J3.checked-3_4uQ9 path {
  fill: var(--accent-color-dark);
}

.bd-switch-symbol path,
.keybindShortcut-1BD6Z1>span svg g {
  fill: var(--accent-color-dark)!important;
}

.bd-button-danger svg {
  fill: #fff!important;
}

.checkbox-1ix_J3 {
  background-color: none;
  border-color: var(--accent-color-main)!important;
}

.containerDefault--pIXnN:hover .unread-2lAfLh,
.closeButton-1tv5uR:hover,
.bd-switch-body {
  background-color: var(--accent-color-dark)!important;
}

.avatarUploaderIndicator-2G-aIZ,
.option-96V44q:hover,
.option-96V44q:hover:after {
  background-color: var(--accent-color-main)!important;
}

.icon-3Gkjwa,
.buttonWrapper-1ZmCpA,
.attachButton-2WznTc,
.clickable-3rdHwn .icon-22AiRD {
  color: var(--button-no-accent);
}

.colorDefault-2K3EoJ.focused-3afm-j,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.akaBadge-1M-1Gw,
.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9,
.botTagRegular-2HEhHi,
.circleIconButton-1QV--U:hover,
.activeButton-rvKcqq,
.activeButton-rvKcqq:hover,
.jumpButton-3DTcS_:hover,
.topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ,
.navButtonActive-1MkytQ,
.navButton-2gQCx-:hover,
.lookFilled-1Gx00P.colorGreen-29iAKY:hover,
.topPill-30KHOu .themed-OHr7kt.item-PXvHYJ:hover:not(.disabled-1Hwwfb),
.side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ,
.actionButton-uPB8Fs:hover,
.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.circleIconButton-1QV--U.selected-1JjBPm,
.bd-select .bd-select-option.selected,
.bd-select .bd-select-option:hover,
.lookInverted-2D7oAl.colorBrand-3pXr91:hover,
.content-1o0f9g,
.jumpToPresentBar-G1R9s6,
.unread-1xRYoj,
.wrapper-3WhCwL:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.button-11zvza:hover,
.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  color: var(--accent-color-dark);
  background-color: var(--accent-color-main);
}

.circleIconButton-1QV--U,
.childWrapper-anI2G9 {
  color: var(--accent-color-main);
  background-color: var(--background-color-main);
}

.actionButton-uPB8Fs,
.bd-button,
.jumpButton-3DTcS_ {
  color: var(--accent-color-main);
  background-color: var(--accent-color-dark);
}

.keybindShortcut-1BD6Z1 span {
  color: var(--accent-color-dark)!important;
  background-color: var(--accent-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23)!important;
}

.wrapper-3WhCwL,
.lookInverted-2D7oAl.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorGreen-29iAKY,
.searchAnswer-3Dz2-q,
.searchFilter-2ESiM3,
.highlight,
.button-11zvza {
  color: var(--accent-color-main);
  background: var(--accent-color-dark);
}

.scroller-1Bvpku {
  background: var(--background-color-darkest);
}

.button-1ZiXG9,
.button-1ZiXG9:hover,
.menu-3sdvDG,
.unicodeShortcut-15J8Ck {
  background: var(--background-color-dark);
}

.children-19S4PO:after {
  background: var(--background-color-dark)!important;
}

.button-1ZiXG9.selected-LCBEAU,
.topSectionNormal-2-vo2m,
.clickable-25tGDB .header-2V-4Sw:hover,
.bd-addon-list .bd-addon-header,
.searchHeader-2XoQg7,
.inspector-S2gM3e,
.platform-win .sidebar-2K8pFh,
.sidebarRegionScroller-3MXcoP,
.container-UC8Ug1,
.quickswitcher-3JagVE {
  background-color: var(--background-color-dark);
}

.bd-description-wrap,
.bd-footer {
  background-color: var(--background-color-main);
  color: var(--text-color);
}

.categoryFadeBlurple-1j72_A {
  background-color: var(--accent-color-main-opacity)!important;
}

.channelTextArea-2VhZ6z .scrollableContainer-2NUZem,
.search-36MZv-,
.searchBar-6Kv8R2 .searchBarComponent-32dTOx,
.inner-2P4tQO,
.inner-3ErfOT,
.wrapper-1cBijl,
.input-2VB9rf,
.search-1iTphC .searchBox-2_mAlO,
.search-1iTphC .searchBox-2_mAlO:focus,
.search-1iTphC .searchBox-2_mAlO:focus-within,
.bd-select,
.bd-select:hover,
.bd-select.menu-open,
.bd-search-wrapper {
  background-color: var(--background-color-main);
  border: 1px solid var(--accent-color-main);
  border-radius: 5px;
}

.inputDefault-_djjkz.input-cIJ7To[aria-label="Explore popular communities"] {
  border: none;
}

.search-1iTphC .searchBox-2_mAlO:focus,
.search-1iTphC .searchBox-2_mAlO:focus-within {
  box-shadow: none;
}

.contentWrapper-SvZHNd,
.contentRegionScroller-26nc1e,
.peopleColumn-29fq28,
.scroller-1d5FgU,
.form-77IDep,
.bd-select .bd-select-option,
.chatContent-a9vAAp,
.modeSelected-346R90 .content-1x5b-n,
.containerDefault--pIXnN:hover .listDefault-3ir5aS,
.uploadModal-2ifh8j .inner-3nWsbo,
.body-3ND3kc,
.premiumContainer-2Iux5m,
.container-1CE3eW {
  background-color: var(--background-color-main);
}

.closeButton-1tv5uR {
  border-color: var(--accent-color-main)!important;
}

.button-38aScr .attachButtonPlus-jWVFah {
  fill: var(--button-no-accent);
}

.top-28JiJ- .selected-3s45Ha.themed-OHr7kt.item-PXvHYJ,
.top-28JiJ- .themed-OHr7kt.item-PXvHYJ:hover {
  color: var(--accent-color-main);
  border-bottom-color: var(--accent-color-main);
}

.container-1r6BKw.themed-ANHk51,
.searchBar-6Kv8R2,
.header-2V-4Sw,
.menu-3sdvDG,
.children-rWhLdy .background-1QDuV2 {
  background-color: var(--background-color-dark);
  box-shadow: 0 3px 6px -6px var(--background-color-darker);
}

.background-1QDuV2 .fieldList-21DyL8 {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px -6px var(--background-color-darker);
}

.isUnread-3Ef-o9 {
  border-color: var(--accent-color-main);
}

.unreadPillCapStroke-7rkHbg {
  color: var(--accent-color-main);
  fill: var(--accent-color-main);
}

.form-2fGMdU::before {
  background: var(--background-color-main)!important;
}

.container-3auIfb {
  background-color: var(--accent-color-dark)!important;
}

.container-3w7J-x {
  border-right: 1px solid var(--accent-color-dark);
  border-left: 1px solid var(--accent-color-dark);
  background-color: var(--background-color-main);
}

.container-3baos1,
.container-3baos1 .avatar-SmRMf2 {
  border-right: 1px solid var(--accent-color-dark);
  border-left: 1px solid var(--accent-color-dark);
  box-shadow: 0 -1px 1px var(--accent-color-dark);
  background-color: var(--background-color-dark);
}

.sidebar-2K8pFh {
  width: var(--channels-width);
}

.button-14-BFJ.enabled-2cQ-u7:hover,
.button-14-BFJ.enabled-2cQ-u7 {
  background: none;
}

.containerDefault-3tr_sE,
.containerDragAfter-Zk9oyx,
.containerDragBefore-1YqewQ,
.containerUserOver-98-yc7 {
  padding-top: 5px;
}

.name-23GUGE {
  font-size: var(--main-font-size);
}

.iconContainer-1BBaeJ {
  margin-right: 3px;
}

.content-1x5b-n {
  padding: 0 3px;
  margin-left: 5px;
}

.mainContent-u_9PKf {
  padding: 2px 0;
}

.members-1998pB,
.members-1998pB>div,
.nowPlayingColumn-2sl4cE {
  border-left: 1px solid var(--accent-color-dark);
  background-color: var(--background-color-main);
}

.membersWrap-2h-GB4 {
  min-width: auto;
  flex-basis: var(--members-width);
}

.membersWrap-2h-GB4 .members-1998pB {
  width: var(--members-width);
}

.scroller-1JbKMe {
  border-right: 1px solid var(--accent-color-dark);
  border-left: 1px solid var(--accent-color-dark);
  background-color: var(--background-color-main);
}

.members-1998pB .membersGroup-v9BXpm {
  padding-top: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: var(--main-font-size);
  font-weight: 500;
  text-align: center;
  transition: all 0.15s ease-in-out;
  opacity: 0.85;
}

.members-1998pB .membersGroup-v9BXpm[style*="color:"] {
  opacity: 1;
}

.members-1998pB .membersGroup-v9BXpm:before {
  content: "";
  height: 1px;
  flex-grow: 6;
  background: linear-gradient(to left, currentColor 50%, transparent);
  margin-right: 3px;
}

.members-1998pB .membersGroup-v9BXpm:after {
  content: "";
  height: 1px;
  flex-grow: 6;
  background: linear-gradient(to right, currentColor 50%, transparent);
  margin-left: 3px;
}

.avatar-3uk_u9 .wrapper-3t9DeA {
  width: 20px !important;
  height: 20px !important;
}

.avatar-3uk_u9 {
  margin-right: 1px;
}

.name-uJV0GL {
  font-size: var(--main-font-size);
  line-height: 20px;
}

.layout-2DM8Md {
  height: 28px;
  padding: 0;
}

.container-2ax-kl {
  font-size: var(--main-font-size);
  text-transform: none;
  color: var(--text-color);
  font-weight: 500;
}

.members-1998pB .membersGroup-v9BXpm {
  font-size: var(--main-font-size);
  text-transform: none;
  color: var(--accent-color-main)!important;
  font-weight: 500;
}

.channel-2QD9_O:hover {
  background: var(--accent-color-main);
}

.divider-JfaTT5 {
  border-top: thin solid var(--accent-color-main);
}

.header-ykumBX {
  position: relative;
  padding: 16px;
  background-color: var(--background-color-dark);
  box-shadow: 0 3px 6px -6px var(--background-color-darker);
}

.messageGroupWrapper-o-Zw7G,
.searchResult-9tQ1uo,
.searchResultsWrap-3-pOjs {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.bd-addon-list .bd-addon-card {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.pill-1aYSec .wrapper-sa6paO {
  height: 30px;
  margin-top: -5px;
}

.anchor-3Z-8Bb .iconWrapper-2OrFZ1 {
  display: none;
}

.resultsGroup-r_nuzN .plusIcon-v0BTrL {
  color: var(--accent-color-dark)!important;
}

.tab-2j5AEF.selected-2LAck8 {
  color: var(--accent-color-dark);
  background-color: var(--accent-color-main)!important;
}

.connectedAccount-36nQx7 {
  border: none;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.flowerStarContainer-3zDVtj svg path {
  fill: var(--accent-color-main);
}

.childContainer-1wxZNh svg path {
  fill: var(--accent-color-dark);
}

.channelName-1JRO3C {
  background: var(--background-color-main);
  color: var(--text-color);
}

.barFill-23-gu- {
  background: var(--accent-color-main);
}

.grabber-3mFHz2 {
  background-color: var(--accent-color-main);
  border-color: var(--accent-color-dark);
}

.container-1CE3eW {
  border-color: var(--accent-color-dark);
}

.item-3HknzM.themed-OHr7kt[aria-controls="ADD_FRIEND-tab"],
.item-PXvHYJ.themed-OHr7kt[aria-controls="Discord Nitro-tab"] {
  color: var(--accent-color-main)!important;
  background-color: var(--accent-color-dark)!important;
}

.peopleListItem-2nzedh {
  border-top: 1px solid var(--accent-color-dark);
}

.arrow-hynWUl {
  filter: invert(80%) sepia(100%) saturate(1099%) hue-rotate(210deg) brightness(100%) contrast(100%);
}

.arrowIcon-1EMN73 {
  filter: invert(40%) sepia(100%) saturate(1077%) hue-rotate(211deg) brightness(100%) contrast(100%);
}

.header-3msK0M {
  overflow: hidden;
}

.embedFull-2tM8-- {
  background-color: var(--background-color-main);
  border-left: 4px solid var(--accent-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.blockquoteContainer-U5TVEi blockquote {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.markup-2BOw-j code,
.messageAttachment-1aDidq {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.blockquoteContainer-U5TVEi .blockquoteDivider-2hH8H6 {
  background-color: var(--accent-color-main);
}

.container-3ayLPN {
  background-color: var(--background-color-main)!important;
}

.option-96V44q:after {
  background: var(--background-color-main)!important;
}

.secondary-dIudih:hover,
.tertiary-aMXF0g:hover:not(.disabled-3Njyym) {
  color: var(--accent-color-dark);
  background-color: var(--accent-color-main);
}

.secondary-dIudih,
.tertiary-aMXF0g {
  color: var(--accent-color-main);
  background-color: var(--accent-color-dark);
}

.collapseButton-2ZsEjz {
  color: var(--accent-color-main);
}

.channelHeader-3Gd2xq {
  background-color: var(--background-color-dark);
}

.channel-3pEHab {
  padding-bottom: 5px;
}

.messages-3G3erD {
  border-radius: 0;
}

.messageContainer-gbhlwo {
  border-radius: 0;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
  padding: 0;
}

.channelHeader-3Gd2xq .closeButton-1152MI,
.channelHeader-3Gd2xq .button-1-5Aqk {
  margin-right: 8px;
}

.container-3iAQ-0 .cozy-3raOZG .messageContent-2qWWxC {
  margin-bottom: 8px;
}

.subscribeTooltipWrapper-1JoUuw {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.subscribeTooltipWrapper-1JoUuw:after {
  border-bottom-color: var(--background-color-main);
}

.card-3DjzTQ:hover {
  background-color: var(--background-color-main);
}

.card-3DjzTQ,
.ctaBar-2UsjF2,
.perk-2WeBWW {
  background-color: var(--background-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.perksModal-fSYqOq,
.tierBody-16Chc9 {
  background-color: var(--background-color-main)!important;
}

.tierHeaderLocked-1s2JJz {
  background-color: var(--background-color-dark)!important;
  color: var(--text-color)!important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6 {
  color: var(--accent-color-main)!important;
  background: var(--accent-color-dark)!important;
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6 .giftIcon-ZxlWk5 {
  color: var(--accent-color-main);
}

.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover .giftIcon-ZxlWk5 {
  color: var(--accent-color-dark);
}

.tierUnlocked-25K6Kv {
  color: var(--accent-color-main)!important;
  background-color: var(--accent-color-dark)!important;
}

.tierMarkerBackground-3q29am {
  background-color: var(--background-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.barBackground-2EEiLw {
  background-color: var(--accent-color-dark)!important;
}

.barForeground-3KglC8,
.barSecondary-3B1aP2 {
  background-color: var(--accent-color-main);
}

.selectedTier-1JkO7i .tierMarker-5HkGJ_ {
  background-color: var(--accent-color-main)!important;
}

.selectedTier-1JkO7i .tierMarker-5HkGJ_ svg path,
.tierMarkerAccomplished-2MiXeg svg path {
  fill: var(--accent-color-dark);
}

.tierMarkerInProgress-24LMzJ svg path {
  fill: var(--accent-color-main);
}

.tierMarkerAccomplished-2MiXeg.tierMarker-5HkGJ_ {
  background: var(--accent-color-main)!important;
}

.selectedTier-1JkO7i .tierMarkerLabelText-F_zS1F {
  color: var(--text-color)!important;
}

.tierMarkerLabelPlusIcon-1OS7E9 {
  color: var(--accent-color-main);
}

.markup-2BOw-j code {
  background-color: var(--background-color-main);
  color: var(--text-color);
}

.headerNormal-T_seeN {
  background-color: var(--background-color-dark)!important;
}

.headerTagUsernameNoNickname-2_H881 {
  color: var(--text-color);
}

.activityUserPopout-2yItg2 .headerTextNormal-2mGWX3 {
  color: var(--accent-color-main)!important;
}

.timeBarUserPopout-AWPFf2 .barInner-3NDaY_ {
  background-color: var(--accent-color-main);
}

.timeBarUserPopout-AWPFf2 .bar-3urHkF {
  background-color: var(--accent-color-dark);
}

.timeBarUserPopout-AWPFf2 .textLeft-3EZXG6,
.timeBarUserPopout-AWPFf2 .textRight-1XO5Ye {
  color: var(--accent-color-main);
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ {
  border: none;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
  border: none;
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.body-3iLsc4,
.footer-1fjuF6 {
  background-color: var(--background-color-main)!important;
  color: var(--text-color);
}

.headerSpotify-zpWxgT.header-2BwW8b,
.headerXbox-3G-4PF.header-2BwW8b,
.headerPlaying-j0WQBV.header-2BwW8b,
.headerStreaming-2FjmGz.header-2BwW8b {
  background-color: var(--background-color-dark);
  color: var(--text-color);
}

.closedFolderIconWrapper-2sTcE6,
.expandedFolderBackground-1cujaW,
.expandedFolderIconWrapper-Huv7rA {
  background-color: var(--accent-color-dark);
}

.expandedFolderIconWrapper-Huv7rA svg path {
  fill: var(--accent-color-main);
}

.container-3RCQyg .card-3RzMcx {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.card-3RzMcx .arrow-3bRNiS {
  color: var(--accent-color-main);
}

.modal-1k91nT .header-1TKi98 {
  background-color: var(--background-color-dark);
}

.modal-1k91nT .scroller-2hZ97C,
.modal-1k91nT .footer-1FPmkC,
.modal-1k91nT .footer-2gL1pp {
  background-color: var(--background-color-main);
}

.modal-1k91nT .lookOutlined-3sRXeN.colorGreen-29iAKY {
  border: none;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.modal-1k91nT .input-cIJ7To:not(.inputDefault-_djjkz) {
  background-color: var(--background-color-main);
  border: 1px solid var(--accent-color-main);
  border-radius: 5px;
}

.modal-1k91nT .content-1LAB8Z {
  border-radius: 0;
}

.channelTextArea-2VhZ6z.highlighted-2eSV1B {
  box-shadow: 0 0 4px var(--accent-color-main);
}

.modal-1k91nT .css-gvi9bl-control:hover,
.modal-1k91nT .css-6fzn47-control:hover,
.modal-1k91nT .css-17e1tep-control:hover {
  box-shadow: 0 0 4px var(--accent-color-main);
}

.modal-1k91nT .css-gvi9bl-control,
.modal-1k91nT .css-6fzn47-control,
.modal-1k91nT .css-17e1tep-control {
  background-color: var(--background-color-main);
  border: 1px solid var(--accent-color-main);
  border-radius: 5px;
}

.modal-1k91nT .css-1fhf191 svg path {
  fill: var(--accent-color-main);
}

.modal-1k91nT .css-3vaxre-menu {
  background-color: var(--background-color-main);
}

.modal-1k91nT .css-rzbxvl-option:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.modal-1k91nT .clear-1pMieT .icon-3cZ1F_:hover {
  color: var(--accent-color-main);
}

.container-3RCQyg .emptyChannelIcon-cc932w {
  background-color: var(--accent-color-dark);
}

.colorDanger-4gmAY0 {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.colorDanger-4gmAY0 .button-2DhvE9 {
  border: none;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.colorDanger-4gmAY0 .button-2DhvE9:hover {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.rtcConnectionQualityFine-2J6i8z .pingForeground-2uAOZ3,
.rtcConnectionStatusConnected-VRZDjy {
  color: var(--accent-color-main);
}

.button-1YfofB.buttonColor-7qQbGO.fauxDisabled-2ik0Vw {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
  width: 5px;
}

.button-1YfofB.buttonColor-7qQbGO.fauxDisabled-2ik0Vw:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.wrapper-24pKcD .container-1giJp5 {
  box-shadow: 0 1px 2px var(--accent-color-main);
  background-color: var(--background-color-dark);
}

.actionButtons-14eAc_ {
  margin-left: 4px;
}

.form-26zE04 .content-1LAB8Z {
  background-color: var(--background-color-dark);
}

.form-26zE04 .footer-2gL1pp {
  background-color: var(--background-color-main);
}

.animatorTop-2Y7x2r .container-2x5lvQ .header-2C89wJ {
  background-color: var(--background-color-dark);
  color: var(--text-color);
}

.animatorTop-2Y7x2r .container-2x5lvQ section {
  background-color: var(--background-color-main);
  color: var(--text-color);
}

.container-2x5lvQ .secured-1Yihly,
.container-2x5lvQ .debugButton-1Zec0y {
  color: var(--accent-color-main);
}

.container-2x5lvQ .secured-1Yihly:before {
  filter: invert(0%) sepia(100%) saturate(1099%) hue-rotate(216deg) brightness(100%) contrast(100%);
}

.mention-1f5kbO:active {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.clickable-1JJAn8:hover .layout-2DM8Md {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.clickable-1JJAn8:hover .layout-2DM8Md .activityText-yGKsKm {
  color: var(--accent-color-dark);
}

.rail-2CbP6L .wrapper-2Gsate {
  background-color: var(--background-color-darker);
}

.section-Kprrfe .selected-3xBBKs {
  background-color: var(--accent-color-dark);
}

.section-Kprrfe .selected-3xBBKs .icon-2VCx8O {
  color: var(--accent-color-main);
}

.scroller-3gAZLs .itemWrapper-14KrHY {
  background-color: var(--background-color-main);
}

.scroller-3gAZLs .itemWrapper-14KrHY .selected-1Tbx07 {
  background-color: var(--background-color-main);
}

.selected-1Tbx07 .usageWrapper-UN_ki6 .colorInteractiveActive-3Ip9Eu {
  color: var(--accent-color-main);
}

.selected-1Tbx07 .usageWrapper-UN_ki6 .option-1B5ZV8 {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.selected-1Tbx07 .usageWrapper-UN_ki6 .optionalHeader-mLQoIx {
  padding-left: 0;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.focusLock-Ns3yie .footer-2gL1pp,
.focusLock-Ns3yie .content-1LAB8Z,
.focusLock-Ns3yie .header-3ydO_m,
.focusLock-Ns3yie .header-3bB_GQ,
.focusLock-Ns3yie .header-2xfEYR,
.focusLock-Ns3yie .header-1TKi98,
.focusLock-Ns3yie .phoneVerificationModal-OzcDc3,
.phoneField-38N1bJ .inputField-aNPXsv {
  background-color: var(--background-color-main);
}

.focusLock-Ns3yie .content-1LAB8Z {
  border-radius: 0;
}

.questionMark-3qBhGj .icon-3zLVMD {
  color: var(--accent-color-main);
}

.questionMark-3qBhGj {
  background-color: var(--accent-color-dark);
}

.questionMark-3qBhGj:hover .icon-3zLVMD {
  color: var(--accent-color-dark);
}

.questionMark-3qBhGj:hover {
  background-color: var(--accent-color-main);
}

.phoneVerificationModal-OzcDc3 .field-wKpjTl {
  background-color: var(--background-color-main);
  border: 1px solid var(--accent-color-main);
  border-radius: 5px;
}

.input-cIJ7To.focused-1mmYsC,
.input-cIJ7To:focus,
.input-cIJ7To:hover,
.input-cIJ7To {
  border-color: var(--accent-color-main);
}

.contentColumnDefault-1VQkGM .accountList-33MS45,
.contentColumnDefault-1VQkGM .accountBtn-2Nozo3 .accountBtnInner-sj5jLs {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.contentColumnDefault-1VQkGM .connectionHeader-2MDqhu,
.contentColumnDefault-1VQkGM .connectionOptionsWrapper-3KIj1Z {
  background-color: var(--background-color-main);
}

.contentColumnDefault-1VQkGM .connectionList-3pzR-1 {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.contentColumnDefault-1VQkGM .feature-2w65J5 {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.paypalInput-3MddcM {
  border-color: var(--accent-color-main)!important;
}

.modal-1qeMox .lookOutlined-3sRXeN.colorBrand-3pXr91 {
  border: none;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.modal-1qeMox .lookOutlined-3sRXeN.colorBrand-3pXr91:hover {
  border: none;
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.codeRedemptionRedirect-1wVR4b {
  border: none;
  color: var(--text-color);
  background-color: var(--background-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.sidebar-CFHs9e .header-2RyJ0Y .themed-OHr7kt {
  color: var(--text-color);
}

.radioBar-bMNUI- {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.radioBar-bMNUI- .title-3BE6m5 {
  color: var(--text-color);
}

.radioBar-bMNUI- svg path {
  fill: var(--accent-color-dark);
}

.connectionDelete-2Odoln:hover {
  color: var(--accent-color-main);
}

.container-2_Tvc_ .title-31JmR4 {
  color: var(--text-color);
}

.connectionOptions-YE9FAM .subEnabledTitle-2ElRo_ {
  color: var(--text-color);
}

.lookLink-9FtZy-.colorPrimary-3b3xI6 {
  color: var(--text-color)!important;
}

.bar-2Qqk5Z {
  background: var(--accent-color-dark)!important;
}

.css-gvi9bl-control,
.css-6fzn47-control,
.css-17e1tep-control,
.css-gvi9bl-control:hover,
.css-17e1tep-control:hover,
.css-6fzn47-control:hover {
  border-color: var(--accent-color-main);
}

.css-ku6vh5-indicatorContainer,
.css-ku6vh5-indicatorContainer:hover {
  color: var(--accent-color-main);
}

.css-3vaxre-menu {
  background-color: var(--background-color-main);
  color: var(--text-color);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.soundRow-7krrdT:hover .soundIcon-2ketvd .icon-GiGwrE {
  color: var(--accent-color-main);
}

.card-FDVird:before {
  background-color: var(--background-color-main)!important;
  border: none;
}

.editIcon-13gaox {
  filter: invert(42%) sepia(100%) saturate(1099%) hue-rotate(210deg) brightness(100%) contrast(100%);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  color: var(--accent-color-main)!important;
  background-color: var(--accent-color-dark)!important;
}

.container-CpszHS:not(.disabled-29eJ21):hover {
  border-color: rgba(178, 136, 230, 0.3);
}

.activeGame-14JI7o.notDetected-33MY4s {
  background-color: var(--background-color-main);
  color: var(--text-color);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.addGamePopout-2RY8Ju {
  background-color: var(--background-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23)!important;
}

.addGamePopout-2RY8Ju .cancelButton-10XRsm {
  color: var(--text-color)!important;
}

.notificationSettings-1NQKPR .wrapper-3jrx9n {
  border: 2px solid var(--accent-color-main);
}

.wrapper-3jrx9n .selected-mKYnfr.option-n0icdO {
  border-color: var(--accent-color-main);
  background-color: var(--accent-color-main);
}

.wrapper-3jrx9n .option-n0icdO:hover {
  background-color: var(--accent-color-main);
}

.bd-sidebar-header .bd-icon:hover {
  fill: var(--accent-color-main);
}

.floating-window.resizable {
  background-color: var(--background-color-main);
  color: var(--text-color);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.floating-window-titlebar {
  background-color: var(--background-color-darker);
  color: var(--text-color);
}

.floating-window #bd-editor-controls {
  background-color: var(--background-color-dark);
  color: var(--text-color);
}

#bd-editor-controls button {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

#bd-editor-controls button:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.checkbox-3kaeSU .checkboxInner-3yjcPe span {
  border-color: var(--accent-color-main)!important;
}

.checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked+span {
  background-color: var(--accent-color-main);
}

.checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked+span:after {
  border-color: var(--accent-color-dark);
}

.monaco-editor .margin {
  background-color: var(--background-color-dark)!important;
}

.bd-controls>.bd-addon-button svg {
  fill: var(--accent-color-main);
}

.bd-controls>.bd-addon-button:hover svg {
  fill: var(--accent-color-dark);
}

.bd-search-wrapper>svg {
  fill: var(--accent-color-main);
}

.bd-addon-views .bd-view-button svg {
  fill: var(--accent-color-main);
}

.bd-addon-views .bd-view-button {
  background-color: var(--accent-color-dark);
}

.bd-addon-views .bd-view-button.selected svg {
  fill: var(--accent-color-dark);
}

.bd-addon-views .bd-view-button.selected {
  background-color: var(--accent-color-main);
}

.bd-button:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.layer-v9HyYc .menu-3sdvDG {
  margin-left: 22px;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.layer-v9HyYc .container-enaOkj {
  background-color: var(--background-color-dark);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.selected-31Nl7x .header-2V-4Sw {
  background-color: var(--background-color-dark);
}

.messagesPopoutWrap-1MQ1bW {
  background-color: var(--background-color-dark);
}

.featureGrid-3-fNl- .feature-2w65J5 {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.peopleListItem-2nzedh:hover {
  background-color: var(--background-color-main);
}

.actionButton-uPB8Fs.highlight-Lf97TE {
  background-color: var(--accent-color-dark);
}

.channelTextArea-rNsIhG .autocomplete-1vrmpx {
  background-color: var(--background-color-main);
}

.autocompleteRowVertical-q1K4ky .selected-1Tbx07 {
  background-color: var(--accent-color-main);
}

.selected-1Tbx07 .colorInteractiveActive-3Ip9Eu,
.selected-1Tbx07 .colorInteractiveNormal-PB7JN3 {
  color: var(--accent-color-dark);
}

.wrapper-2IKwZK .description-QP9Ktn,
.wrapper-2IKwZK .source-3DBj4z {
  color: var(--text-color);
}

.wrapper-1-Fsb8.categoryHeader-O1zU94 {
  background-color: var(--background-color-dark);
}

.wrapper-2siovq .icon-2VCx8O {
  color: var(--accent-color-main);
}

.wrapper-2siovq .icon-2VCx8O svg path {
  fill: var(--accent-color-dark);
}

.selected-1Tbx07 .autocompleteRowIcon-2VJmzt .icon-3ZzoN7 {
  color: var(--accent-color-dark);
}

.form-2fGMdU .container-2fRDfG {
  background-color: var(--accent-color-main);
}

.form-2fGMdU .container-2fRDfG .colorHeaderSecondary-3Sp3Ft,
.form-2fGMdU .container-2fRDfG .closeButton-37O8QC {
  color: var(--accent-color-dark);
}

.repliedMessage-VokQwo:before {
  border-left: var(--spine-width) solid var(--accent-color-main);
  border-bottom: 0 solid var(--accent-color-main);
  border-right: 0 solid var(--accent-color-main);
  border-top: var(--spine-width) solid var(--accent-color-main);
}

.cardWrapper-2R6-SX .checkmark-3rush5 {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.radioBar-bMNUI- .foreground-SshK2E {
  fill: var(--accent-color-main);
}

.inputWrapper-31_8H8 .inputPrefix-1gzNds {
  color: var(--accent-color-main);
}

.switchIcon-_4Efyi path {
  fill: var(--accent-color-main);
}

.addMemberRow-3-w-9X.selectedRow-1QP7qb,
.addMemberRow-3-w-9X {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.addMemberRow-3-w-9X.selectedRow-1QP7qb svg path,
.addMemberRow-3-w-9X svg path {
  fill: var(--accent-color-main);
}

.root-1gCeng {
  background-color: var(--background-color-main)!important;
}

.colorStatusGreen-2saF4_.protip-283HFv {
  color: var(--accent-color-main);
}

.categorySection-2sgp74 .arrow-gKvcEx path {
  fill: var(--accent-color-main);
}

.categorySection-2sgp74 .wrapper-1-Fsb8 {
  background-color: var(--background-color-dark);
}

.emojiPickerInExpressionPicker-3IzIcv .categoryList-2Kzf65 {
  background-color: var(--background-color-darker);
}

.emojiPickerListWrapper-fz8KNK .listItems-1uJgMC {
  left: 0px!important;
}

.list-donH_Z .categoryItemDefaultCategorySelected-_HCKoz .categoryIcon-1SvUHG {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.list-donH_Z .categoryItemDefaultCategorySelected-_HCKoz:hover .categoryIcon-1SvUHG {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.list-donH_Z .categoryItemDefaultCategory-aBZ6nJ {
  background-color: var(--accent-color-dark);
}

.list-donH_Z .categoryItemDefaultCategory-aBZ6nJ path {
  fill: var(--accent-color-main);
}

.list-donH_Z .categoryItemDefaultCategory-aBZ6nJ:hover {
  background-color: var(--accent-color-main);
}

.list-donH_Z .categoryItemDefaultCategory-aBZ6nJ:hover path {
  fill: var(--accent-color-dark);
}

.emojiItem-14v6tW.emojiItemSelected-1aLkfV {
  background-color: var(--accent-color-dark);
}

.categorySection-2sgp74 .header-19cWci.interactive-BzuinF:hover:hover {
  color: var(--accent-color-main);
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j {
  background-color: var(--background-color-main);
}

.modal-3c3bKg .inner-1ilYF7 .uploadModal-2ifh8j,
.modal-3c3bKg .inner-1ilYF7 .uploadModal-2ifh8j .footer-3mqk7D {
  background-color: var(--background-color-main)!important;
}

.notice-3uyY6c.notice-3bPHh- {
  background-color: var(--accent-color-main);
}

.notice-3uyY6c.notice-3bPHh- .colorStandard-2KCXvj {
  color: var(--accent-color-dark);
}

.notice-3uyY6c.notice-3bPHh- .lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.container-19nk2r .guildSidebar-2OCzWB {
  background-color: var(--background-color-dark);
}

.container-19nk2r .formFieldWrapper-malor5 {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.container-19nk2r .formFieldWrapper-malor5 .colorMuted-HdFt4q {
  color: var(--accent-color-main);
}

.focusLock-Ns3yie .footer-2gL1pp .lookFilled-1Gx00P.colorGreen-29iAKY:disabled {
  background-color: var(--accent-color-dark);
}

.focusLock-Ns3yie .footer-2gL1pp .lookFilled-1Gx00P.colorGreen-29iAKY:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.cardWarning-2yPNAa {
  background-color: var(--accent-color-main);
  border-color: var(--accent-color-main);
}

.cardWarning-2yPNAa .warning-3AwWn_ {
  color: var(--accent-color-dark);
}

.contentRegionScroller-26nc1e .button-38aScr.lookOutlined-3sRXeN.colorPrimary-3b3xI6 {
  border: none;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.contentRegionScroller-26nc1e .button-38aScr.lookOutlined-3sRXeN.colorPrimary-3b3xI6:hover {
  border: none;
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.noticeRegion-1YviSH .container-2VW0UT {
  background-color: var(--background-color-dark)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.noticeRegion-1YviSH .container-2VW0UT .message-c9-HCF {
  color: var(--text-color)!important;
}

.divider-3wNib3 {
  border-color: var(--accent-color-dark)!important;
}

.css-4h5swf-singleValue svg.icon-JJBzjE.lighten-2aYaaU path {
  color: var(--accent-color-main)!important;
}

svg.icon-JJBzjE.lighten-2aYaaU {
  opacity: 1.0!important;
}

.addRoleButton-3Y-nzm:hover .addRoleIcon-3YjErH {
  filter: invert(130%) sepia(100%) saturate(1099%) hue-rotate(216deg) brightness(100%) contrast(100%);
}

.roleOverflow-1zjC9k {
  color: var(--accent-color-dark);
}

.item-2J2GlB.selectedBrand-1UKrSX {
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
}

.item-2J2GlB.selectedBrand-1UKrSX:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.content-3YMskv .item-2J2GlB:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

.expandForeground-1nZ4VR {
  stroke: var(--accent-color-main)!important;
}

.descriptionBox-1EKQKL {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.features-2PXC_Z .featureCard-1RR4Tl {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.tiers-2J8eY9 .tier-3H4BXk {
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.tiers-2J8eY9 .tier-3H4BXk .tierHeaderLocked-1a2opw {
  background-color: var(--background-color-dark);
  color: var(--text-color);
}

.tiers-2J8eY9 .tier-3H4BXk .tierBody-x9kBBp {
  background-color: var(--background-color-main);
  color: var(--text-color);
}

.tiers-2J8eY9 .tier-3H4BXk .tierLock-1oFMOZ {
  color: var(--accent-color-main);
  opacity: 0.6;
}

.tiers-2J8eY9 .tier-3H4BXk svg.tierIcon-36mHr9 path {
  fill: var(--accent-color-main);
}

.themed-OHr7kt.item-PXvHYJ[aria-selected="true"][aria-controls="GUILD_PREMIUM-tab"] {
  background-color: var(--accent-color-main)!important;
  color: var(--accent-color-dark)!important;
}

.themed-OHr7kt.item-PXvHYJ[aria-selected="false"][aria-controls="GUILD_PREMIUM-tab"] {
  background-color: var(--accent-color-dark)!important;
  color: var(--accent-color-main)!important;
}

.categoryItem-1QIroW.selectedCategoryItem-FHKU_o .itemInner-gPkiWb {
  background-color: var(--accent-color-main);
}

.categoryItem-1QIroW.selectedCategoryItem-FHKU_o .name-uJV0GL {
  color: var(--accent-color-dark);
}

.categoryItem-1QIroW.selectedCategoryItem-FHKU_o .itemInner-gPkiWb .avatar-3uk_u9 path {
  fill: var(--accent-color-dark);
}

.bd-server-card,
.bd-server-card:hover,
.bd-server-card:focus {
  background-color: var(--background-color-main)!important;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

#bd-pub-button {
  border-radius: 50%;
  background-color: var(--accent-color-dark);
  color: var(--accent-color-main);
  font-size: 10px;
  line-height: 27px;
  height: 27px;
  transition: none;
}

#bd-pub-button:hover {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
}

#bd-pub-li {
  height: 27px;
}

.lookLink-9FtZy-.colorBrand-3pXr91 {
  color: var(--accent-color-main);
}

.lookLink-9FtZy-.colorBrand-3pXr91:hover .contents-18-Yxp {
  background-image: none;
  color: var(--accent-color-main);
}

.avatarUploader-3XDtmn .sizeInfo-SKMPPw {
  color: var(--accent-color-main);
}

.containerDragAfter-Zk9oyx:before,
.containerDragBefore-1YqewQ:before,
.containerDragAfter-3Fp7LC:before,
.containerDragAfter-3Fp7LC:after,
.containerDragBefore-3iTCc7:before {
  background-color: var(--accent-color-main);
}

.notice-3bPHh-.colorDanger-4gmAY0 {
  border-radius: 0;
}

.notice-3bPHh-.colorDanger-4gmAY0 .closeButton-3cJIM4 {
  filter: invert(120%) sepia(100%) saturate(1099%) hue-rotate(216deg) brightness(100%) contrast(100%);
}

.messageContainer-1ei2zM .jumpButton-2dvRSC:hover {
  background-color: var(--accent-color-main);
}

.messageContainer-1ei2zM .jumpButton-2dvRSC {
  background-color: var(--accent-color-dark);
}

.messageContainer-1ei2zM .jumpButton-2dvRSC .text-3KVtey {
  color: var(--accent-color-main);
}

.messageContainer-1ei2zM .jumpButton-2dvRSC:hover .text-3KVtey {
  color: var(--accent-color-dark);
}

.recentMentionsPopout-3rCiI6 .channel-3pEHab {
  margin-bottom: 16px;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.toast-g4bfgI.colorSuccess-6GreWs .bg-8df5St {
  background-color: var(--accent-color-main);
}

.toast-g4bfgI.colorSuccess-6GreWs .inner-6Fsw34 {
  color: var(--accent-color-dark);
}

.messageContainer-gbhlwo .jumpButton-2F6EMx:hover {
  background-color: var(--accent-color-main);
}

.messageContainer-gbhlwo .jumpButton-2F6EMx {
  background-color: var(--accent-color-dark);
}

.messageContainer-gbhlwo .jumpButton-2dvRSC .text-3KVtey {
  color: var(--accent-color-main);
}

.messageContainer-gbhlwo .jumpButton-2dvRSC:hover .text-3KVtey {
  color: var(--accent-color-dark);
}

.bd-toast.toast-info {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
  opacity: 0.9;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.bd-toast {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
  opacity: 0.9;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.bd-toast.toast-success {
  background-color: var(--accent-color-main);
  color: var(--accent-color-dark);
  opacity: 0.9;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.toolbar-2bjZV7 {
  background-color: var(--background-color-dark);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.toolbar-2bjZV7 .active-2HPddW .icon-KgGMGo,
.toolbar-2bjZV7 .hover-28QbSq:hover .icon-KgGMGo {
  color: var(--accent-color-dark);
  background-color: var(--accent-color-main);
}

.toolbar-2bjZV7 .icon-KgGMGo {
  color: var(--accent-color-main);
}

.toolbar-2bjZV7 .divider-24xeUg {
  border-left: 1px solid var(--accent-color-dark);
}

.wrapper-35wsBm {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.reaction-1hd86g {
  background-color: var(--background-color-main);
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.reactionCount-2mvXRV {
  color: var(--accent-color-main);
}

.layer-3QrUeG[aria-label*=SETTINGS] {
    align-items: center;
    justify-content: center;
    background: rgba(0,0,0,0.4);
    z-index: 12;
	display: flex;
    top: -28px;
	padding: 0 30px;
}

.layer-3QrUeG {
    opacity: 1 !important;
    transform: none !important;
    top: 0;
    padding-top: 0;
}

.layer-3QrUeG[aria-label*=SETTINGS] .standardSidebarView-3F1I7i {
    animation: fadeIn 1.5s;
    border-radius: 5px;
    background: var(--background-color-darker);
    position: relative;
    overflow: hidden;
    box-shadow: 0 0 4px var(--accent-color-main);
    width: 100%;
    min-width: 960px;
    max-width: 960px;
    height: 75vh;
    max-height: 650px;
    min-height: 400px;
    padding-top: 30px;
    top: 0;
}

.layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegion-VFTUkN {
    flex: unset;
    z-index: 10;
    border-right: 1px solid var(--accent-color-dark);
}

.layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegion-VFTUkN .sidebarRegionScroller-3MXcoP {
    flex: auto;
}


.layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegion-VFTUkN .sidebar-CFHs9e {
    padding: 10px 0;
    width: auto;
}

.layer-3QrUeG[aria-label=USER_SETTINGS] .side-8zPYf6 > .item-PXvHYJ {
    display: flex;
    align-items: center;
}

.layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegion-VFTUkN .item-PXvHYJ {
    margin: 3px 20px;
    font-size: var(--font-size-main);
    padding: 10px;
    border-radius: 5px;
    color: var(--text-color);
    line-height: normal;
    min-width: 155px;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy {
    flex: unset;
    flex-grow: 1;
    background: transparent;
    position: static;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy::before {
    display: flex;
    align-items: center;
    border-bottom: 1px solid var(--accent-color-dark);
    width: 100%;
    height: 30px;
    position: absolute;
    top: 0;
    left: 0;
    padding: 20px;
    box-sizing: border-box;
    background: var(--background-color-darkest);
    z-index: 0;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .contentColumnDefault-1VQkGM {
    padding: 20px;
    flex-grow: 1;
    max-width: unset;
    min-width: unset;
    display: flex;
    flex-direction: column;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy h2 {
    font-weight: 500;
    font-size: var(--main-font-size);
    color: var(--text-color);
    margin-bottom: 10px;
    line-height: unset;
    text-transform: none;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .toolsContainer-1edPuj {
    padding-top: 0;
    width: auto;
    height: 30px;
    top: 0;
    display: flex;
    align-items: center;
    position: absolute;
    margin: 0;
    right: 15px;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .tools-3-3s-N {
    position: relative;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .tools-3-3s-N .closeButton-1tv5uR {
    border: none;
    width: 30px;
    height: 30px;
    flex: none;
    border-radius: 0;
    transform: none;
    background: transparent;
}

.layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .tools-3-3s-N .keybind-KpFkfr {
    display: none;
}

/*top most titlebar syling - credits to ClearVision Team for the original idea and css*/

.typeWindows-1za-n7 {
  height: 18px;
  width: 100vw;
  margin: 0;
  padding-top: 2px;
  padding-bottom: 2px;
  background: var(--background-color-darkest);
  box-shadow: 0 0 4px var(--accent-color-main);
}

.typeWindows-1za-n7>.wordmark-2iDDfm {
  position: static;
  margin-right: auto;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 1;
  pointer-events: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  order: 1;
}

.typeWindows-1za-n7>.wordmark-2iDDfm:before,
.typeWindows-1za-n7>.wordmark-2iDDfm:after {
  margin-left: 3px;
  font-weight: 500;
  white-space: nowrap;
  order: 1;
}

.typeWindows-1za-n7>.wordmark-2iDDfm:before {
  content: "Materialistic";
  color: var(--text-color);
  font-family: var(--main-font);
  font-size: var(--secondary-font-size);
}

.typeWindows-1za-n7>.wordmark-2iDDfm:after {
  content: "v1.0.0";
  color: var(--accent-color-main);
  font-family: var(--code-font);
  font-size: var(--subtext-font-size);
}

.typeWindows-1za-n7>.wordmark-2iDDfm>svg {
  filter: drop-shadow(0 0 2px var(--accent-color-main));
}
