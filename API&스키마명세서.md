Need to install the following packages:
graphql-markdown@7.3.0
Ok to proceed? (y) 
# Schema Types

<details>
  <summary><strong>Table of Contents</strong></summary>

  * [Query](#query)
  * [Mutation](#mutation)
  * [Subscription](#subscription)
  * [Objects](#objects)
    * [Admin](#admin)
    * [AdminPostCategory](#adminpostcategory)
    * [AdminPostList](#adminpostlist)
    * [AdminPostModel](#adminpostmodel)
    * [AdminPostModelEdge](#adminpostmodeledge)
    * [AdministrativeActionDetail](#administrativeactiondetail)
    * [AdvertisementList](#advertisementlist)
    * [AdvertisementModel](#advertisementmodel)
    * [AdvertisementModelEdge](#advertisementmodeledge)
    * [AnnouncementApplyList](#announcementapplylist)
    * [AnnouncementApplyModel](#announcementapplymodel)
    * [AnnouncementApplyModelEdge](#announcementapplymodeledge)
    * [AnnouncementDashboard](#announcementdashboard)
    * [AnnouncementDashboardForAdminModel](#announcementdashboardforadminmodel)
    * [AnnouncementList](#announcementlist)
    * [AnnouncementModel](#announcementmodel)
    * [AnnouncementModelEdge](#announcementmodeledge)
    * [AnnouncementResultCount](#announcementresultcount)
    * [AnnouncementTempList](#announcementtemplist)
    * [AnnouncementTempModel](#announcementtempmodel)
    * [AnnouncementTempModelEdge](#announcementtempmodeledge)
    * [AuthTokenResponse](#authtokenresponse)
    * [BalanceDetail](#balancedetail)
    * [BankCodeList](#bankcodelist)
    * [BankCodeModel](#bankcodemodel)
    * [BankCodeModelEdge](#bankcodemodeledge)
    * [Banner](#banner)
    * [CRIList](#crilist)
    * [CRIModel](#crimodel)
    * [CRIModelEdge](#crimodeledge)
    * [CategoryList](#categorylist)
    * [CategoryModel](#categorymodel)
    * [CategoryModelEdge](#categorymodeledge)
    * [CommunityCategory](#communitycategory)
    * [CommunityCategoryEdge](#communitycategoryedge)
    * [CommunityCategoryList](#communitycategorylist)
    * [CommunityPost](#communitypost)
    * [CommunityPostEdge](#communitypostedge)
    * [CommunityPostList](#communitypostlist)
    * [CommunityPostReply](#communitypostreply)
    * [CommunityPostReplyEdge](#communitypostreplyedge)
    * [CommunityPostReplyList](#communitypostreplylist)
    * [CommunityReport](#communityreport)
    * [CommunityReportEdge](#communityreportedge)
    * [CommunityReportList](#communityreportlist)
    * [CompanyInfoList](#companyinfolist)
    * [CompanyInfoModel](#companyinfomodel)
    * [CompanyInfoModelEdge](#companyinfomodeledge)
    * [EnterpriseDashboardModel](#enterprisedashboardmodel)
    * [EnterpriseList](#enterpriselist)
    * [Event](#event)
    * [Faq](#faq)
    * [File](#file)
    * [FinancialGraphRow](#financialgraphrow)
    * [FinancialModel](#financialmodel)
    * [FinancialSalesInfo](#financialsalesinfo)
    * [FinancialTable](#financialtable)
    * [FinancialTableRow](#financialtablerow)
    * [FinedAccount](#finedaccount)
    * [IncomeDetail](#incomedetail)
    * [Inquire](#inquire)
    * [InquireEdge](#inquireedge)
    * [InquireList](#inquirelist)
    * [KakaoAccessData](#kakaoaccessdata)
    * [KakaoJWTData](#kakaojwtdata)
    * [LicenseList](#licenselist)
    * [LicenseModel](#licensemodel)
    * [LicenseModelEdge](#licensemodeledge)
    * [MatchPost](#matchpost)
    * [MatchPostCategory](#matchpostcategory)
    * [MatchPostCategoryEdge](#matchpostcategoryedge)
    * [MatchPostCategoryList](#matchpostcategorylist)
    * [MatchPostEdge](#matchpostedge)
    * [MatchPostList](#matchpostlist)
    * [MatchPostType](#matchposttype)
    * [MatchPostTypeEdge](#matchposttypeedge)
    * [MatchPostTypeList](#matchposttypelist)
    * [Member](#member)
    * [MemberCount](#membercount)
    * [MyAnnouncementDashboard](#myannouncementdashboard)
    * [MyAvailableAnnouncementDashboard](#myavailableannouncementdashboard)
    * [MyAvailableAnnouncementDashboardItem](#myavailableannouncementdashboarditem)
    * [MyPointRefundInfo](#mypointrefundinfo)
    * [MyReviewDashboard](#myreviewdashboard)
    * [Notice](#notice)
    * [Notification](#notification)
    * [NotificationEdge](#notificationedge)
    * [NotificationList](#notificationlist)
    * [NotificationStorageList](#notificationstoragelist)
    * [NotificationStorageModel](#notificationstoragemodel)
    * [NotificationStorageModelEdge](#notificationstoragemodeledge)
    * [OpenSourceModel](#opensourcemodel)
    * [PageInfo](#pageinfo)
    * [PageViewsModel](#pageviewsmodel)
    * [PatentDetail](#patentdetail)
    * [PaymentItemModel](#paymentitemmodel)
    * [PaymentList](#paymentlist)
    * [PaymentMethod](#paymentmethod)
    * [PaymentModel](#paymentmodel)
    * [PaymentModelEdge](#paymentmodeledge)
    * [PaymentRefundList](#paymentrefundlist)
    * [PaymentRefundModel](#paymentrefundmodel)
    * [PaymentRefundModelEdge](#paymentrefundmodeledge)
    * [PaymentResponseModel](#paymentresponsemodel)
    * [Point](#point)
    * [PointDashboard](#pointdashboard)
    * [PointEdge](#pointedge)
    * [PointList](#pointlist)
    * [PointRefund](#pointrefund)
    * [PointRefundEdge](#pointrefundedge)
    * [PointRefundList](#pointrefundlist)
    * [PointSubscriptionDashboardForAdmin](#pointsubscriptiondashboardforadmin)
    * [Popup](#popup)
    * [PortfolioList](#portfoliolist)
    * [PortfolioModel](#portfoliomodel)
    * [PortfolioModelEdge](#portfoliomodeledge)
    * [PortfolioRecommendationList](#portfoliorecommendationlist)
    * [PortfolioRecommendationModel](#portfoliorecommendationmodel)
    * [PortfolioRecommendationModelEdge](#portfoliorecommendationmodeledge)
    * [ProfileCompanyInfo](#profilecompanyinfo)
    * [ProfileConsumerInfo](#profileconsumerinfo)
    * [ProfileDashboard](#profiledashboard)
    * [ProfileEngineerInfo](#profileengineerinfo)
    * [ProfileInfoAddress](#profileinfoaddress)
    * [ProfileInfoPhone](#profileinfophone)
    * [ProfileInfoStockholders](#profileinfostockholders)
    * [Report](#report)
    * [ReportEdge](#reportedge)
    * [ReportList](#reportlist)
    * [ReviewList](#reviewlist)
    * [ReviewModel](#reviewmodel)
    * [ReviewModelEdge](#reviewmodeledge)
    * [ServiceManage](#servicemanage)
    * [SignUpResult](#signupresult)
    * [SigunguModel](#sigungumodel)
    * [SubscriptionApplyModel](#subscriptionapplymodel)
    * [UserAllow](#userallow)
    * [UserBlock](#userblock)
    * [UserBlockEdge](#userblockedge)
    * [UserBlockList](#userblocklist)
    * [UserDashboardForAdmin](#userdashboardforadmin)
    * [UserEdge](#useredge)
    * [UserFCMToken](#userfcmtoken)
    * [UserFCMTokenEdge](#userfcmtokenedge)
    * [UserList](#userlist)
    * [UserNotificationSetting](#usernotificationsetting)
    * [UserProfile](#userprofile)
    * [UserProfileEdge](#userprofileedge)
    * [UserSocialLink](#usersociallink)
  * [Inputs](#inputs)
    * [AdminPostCategoryCreateInput](#adminpostcategorycreateinput)
    * [AdminPostCategoryUpdateInput](#adminpostcategoryupdateinput)
    * [AdminPostFilterInput](#adminpostfilterinput)
    * [AdminPostSortInput](#adminpostsortinput)
    * [AdminPostStateFilterInput](#adminpoststatefilterinput)
    * [AdminPostTypeFilterInput](#adminposttypefilterinput)
    * [AdminPostTypeSortInput](#adminposttypesortinput)
    * [AdvertisementCreateInput](#advertisementcreateinput)
    * [AdvertisementFilterInput](#advertisementfilterinput)
    * [AdvertisementLocationEnumFilterInput](#advertisementlocationenumfilterinput)
    * [AdvertisementSortInput](#advertisementsortinput)
    * [AdvertisementStateEnumFilterInput](#advertisementstateenumfilterinput)
    * [AdvertisementUpdateInput](#advertisementupdateinput)
    * [AnnouncementApplyCreateInput](#announcementapplycreateinput)
    * [AnnouncementApplyFilterInput](#announcementapplyfilterinput)
    * [AnnouncementApplySortInput](#announcementapplysortinput)
    * [AnnouncementApplyStateFilter](#announcementapplystatefilter)
    * [AnnouncementCreateInput](#announcementcreateinput)
    * [AnnouncementFieldInfoFilterInput](#announcementfieldinfofilterinput)
    * [AnnouncementFilterInput](#announcementfilterinput)
    * [AnnouncementOrderTypeFilterInput](#announcementordertypefilterinput)
    * [AnnouncementSortInput](#announcementsortinput)
    * [AnnouncementStateFilterInput](#announcementstatefilterinput)
    * [AnnouncementStateSortInput](#announcementstatesortinput)
    * [AnnouncementTempCreateInput](#announcementtempcreateinput)
    * [AnnouncementTempFilterInput](#announcementtempfilterinput)
    * [AnnouncementTempSortInput](#announcementtempsortinput)
    * [AnnouncementTempUpdateInput](#announcementtempupdateinput)
    * [AnnouncementTypeFilterInput](#announcementtypefilterinput)
    * [AnnouncementUpdateInput](#announcementupdateinput)
    * [AnnouncementUpdateInputForAdmin](#announcementupdateinputforadmin)
    * [AnnouncementWorkScopeEnumFilterInput](#announcementworkscopeenumfilterinput)
    * [AnnouncementWorkTypeFilterInput](#announcementworktypefilterinput)
    * [BankCodeFilterInput](#bankcodefilterinput)
    * [BankCodeSortInput](#bankcodesortinput)
    * [BannerCreateInput](#bannercreateinput)
    * [BannerUpdateInput](#bannerupdateinput)
    * [BooleanFilterInput](#booleanfilterinput)
    * [CRIFilterInput](#crifilterinput)
    * [CRIPriorityEnumFilterInput](#cripriorityenumfilterinput)
    * [CRISortInput](#crisortinput)
    * [CategoryCreateInputForAdmin](#categorycreateinputforadmin)
    * [CategoryFilterInput](#categoryfilterinput)
    * [CategoryFilterInputForAdmin](#categoryfilterinputforadmin)
    * [CategorySortInput](#categorysortinput)
    * [CategoryTypeEnumFilterInput](#categorytypeenumfilterinput)
    * [CategoryUpdateInputForAdmin](#categoryupdateinputforadmin)
    * [CommunityCategoryCreateInput](#communitycategorycreateinput)
    * [CommunityCategoryFilterInput](#communitycategoryfilterinput)
    * [CommunityCategoryOrderByInput](#communitycategoryorderbyinput)
    * [CommunityCategoryUpdateInput](#communitycategoryupdateinput)
    * [CommunityPostCreateInput](#communitypostcreateinput)
    * [CommunityPostFilterInput](#communitypostfilterinput)
    * [CommunityPostOrderByInput](#communitypostorderbyinput)
    * [CommunityPostReplyCreateInput](#communitypostreplycreateinput)
    * [CommunityPostReplyFilterInput](#communitypostreplyfilterinput)
    * [CommunityPostReplyOrderByInput](#communitypostreplyorderbyinput)
    * [CommunityPostReplyUpdateInput](#communitypostreplyupdateinput)
    * [CommunityPostUpdateInput](#communitypostupdateinput)
    * [CommunityReportCategoryFilterInput](#communityreportcategoryfilterinput)
    * [CommunityReportCreateInput](#communityreportcreateinput)
    * [CommunityReportFilterInput](#communityreportfilterinput)
    * [CommunityReportOrderByInput](#communityreportorderbyinput)
    * [CommunityReportStateFilterInput](#communityreportstatefilterinput)
    * [CommunityReportTypeFilterInput](#communityreporttypefilterinput)
    * [CommunityReportUpdateInput](#communityreportupdateinput)
    * [CompanyInfoFilterInput](#companyinfofilterinput)
    * [CompanyInfoSortInput](#companyinfosortinput)
    * [DateTimeFilterInput](#datetimefilterinput)
    * [EnterpriseFilterInput](#enterprisefilterinput)
    * [EnterpriseSortInput](#enterprisesortinput)
    * [EventCreateInput](#eventcreateinput)
    * [EventUpdateInput](#eventupdateinput)
    * [FaqCreateInput](#faqcreateinput)
    * [FaqUpdateInput](#faqupdateinput)
    * [FloatFilterInput](#floatfilterinput)
    * [IDFilterInput](#idfilterinput)
    * [InquireCreateInput](#inquirecreateinput)
    * [InquireFilterInput](#inquirefilterinput)
    * [InquireSortInput](#inquiresortinput)
    * [InquireStateFilterInput](#inquirestatefilterinput)
    * [InquireTypeFilterInput](#inquiretypefilterinput)
    * [InquireUpdateInput](#inquireupdateinput)
    * [InquireUpdateInputForAdmin](#inquireupdateinputforadmin)
    * [IntFilterInput](#intfilterinput)
    * [IntSortInput](#intsortinput)
    * [ItemTypeEnumFilterInput](#itemtypeenumfilterinput)
    * [LicenseFilterInput](#licensefilterinput)
    * [LicenseSortInput](#licensesortinput)
    * [MatchPostCategoryCreateInput](#matchpostcategorycreateinput)
    * [MatchPostCategoryFilterInput](#matchpostcategoryfilterinput)
    * [MatchPostCategoryOrderByInput](#matchpostcategoryorderbyinput)
    * [MatchPostCategoryUpdateInput](#matchpostcategoryupdateinput)
    * [MatchPostFilterInput](#matchpostfilterinput)
    * [MatchPostOrderByInput](#matchpostorderbyinput)
    * [MatchPostStateEnumFilterInput](#matchpoststateenumfilterinput)
    * [MatchPostTypeCreateInput](#matchposttypecreateinput)
    * [MatchPostTypeFilterInput](#matchposttypefilterinput)
    * [MatchPostTypeOrderByInput](#matchposttypeorderbyinput)
    * [MatchPostTypeUpdateInput](#matchposttypeupdateinput)
    * [NoticeCreateInput](#noticecreateinput)
    * [NoticeUpdateInput](#noticeupdateinput)
    * [NotificationCreateInput](#notificationcreateinput)
    * [NotificationFilterInput](#notificationfilterinput)
    * [NotificationSortInput](#notificationsortinput)
    * [NotificationStorageCreateInput](#notificationstoragecreateinput)
    * [NotificationStorageFilterInput](#notificationstoragefilterinput)
    * [NotificationStorageSortInput](#notificationstoragesortinput)
    * [NotificationStorageUpdateInput](#notificationstorageupdateinput)
    * [NotificationTypeFilterInput](#notificationtypefilterinput)
    * [NotificationTypeSortInput](#notificationtypesortinput)
    * [OmitObjectType](#omitobjecttype)
    * [PaymentFilterInput](#paymentfilterinput)
    * [PaymentItemCreateInput](#paymentitemcreateinput)
    * [PaymentItemUpdateInput](#paymentitemupdateinput)
    * [PaymentMethodCreateInput](#paymentmethodcreateinput)
    * [PaymentMethodFilterInput](#paymentmethodfilterinput)
    * [PaymentRefundFilterInput](#paymentrefundfilterinput)
    * [PaymentRefundSortInput](#paymentrefundsortinput)
    * [PaymentRefundStateEnumFilterInput](#paymentrefundstateenumfilterinput)
    * [PaymentSortInput](#paymentsortinput)
    * [PaymentStateEnumFilterInput](#paymentstateenumfilterinput)
    * [PaymentUpdateInputForAdmin](#paymentupdateinputforadmin)
    * [PointFilterInput](#pointfilterinput)
    * [PointRefundCreateInput](#pointrefundcreateinput)
    * [PointRefundFilterInput](#pointrefundfilterinput)
    * [PointRefundSortInput](#pointrefundsortinput)
    * [PointRefundStateEnumFilterInput](#pointrefundstateenumfilterinput)
    * [PointSortInput](#pointsortinput)
    * [PointTypeEnumFilterInput](#pointtypeenumfilterinput)
    * [PopupCreateInput](#popupcreateinput)
    * [PopupUpdateInput](#popupupdateinput)
    * [PortfolioConstructionTypeFilter](#portfolioconstructiontypefilter)
    * [PortfolioCreateInput](#portfoliocreateinput)
    * [PortfolioFilterInput](#portfoliofilterinput)
    * [PortfolioRecommendationCreateInput](#portfoliorecommendationcreateinput)
    * [PortfolioRecommendationFilterInput](#portfoliorecommendationfilterinput)
    * [PortfolioRecommendationSortInput](#portfoliorecommendationsortinput)
    * [PortfolioRecommendationStateEnumFilterInput](#portfoliorecommendationstateenumfilterinput)
    * [PortfolioRecommendationUpdateInput](#portfoliorecommendationupdateinput)
    * [PortfolioServicePriceTypeFilter](#portfolioservicepricetypefilter)
    * [PortfolioSortInput](#portfoliosortinput)
    * [PortfolioUpdateInput](#portfolioupdateinput)
    * [PortfolioUpdateInputForAdmin](#portfolioupdateinputforadmin)
    * [ProfileCompanyInfoUpdateInput](#profilecompanyinfoupdateinput)
    * [ProfileConsumerInfoUpdateInput](#profileconsumerinfoupdateinput)
    * [ProfileEngineerInfoUpdateInput](#profileengineerinfoupdateinput)
    * [ProfileInfoAddressInput](#profileinfoaddressinput)
    * [ProfileInfoPhoneInput](#profileinfophoneinput)
    * [ProfileInfoStockholdersInput](#profileinfostockholdersinput)
    * [ProfileTypeFilterInput](#profiletypefilterinput)
    * [ReportCreateInput](#reportcreateinput)
    * [ReportFilterInput](#reportfilterinput)
    * [ReportSortInput](#reportsortinput)
    * [ReportUpdateInput](#reportupdateinput)
    * [ReviewFilterInput](#reviewfilterinput)
    * [ReviewFilterInputForAdmin](#reviewfilterinputforadmin)
    * [ReviewSortInput](#reviewsortinput)
    * [ReviewStateFilterInput](#reviewstatefilterinput)
    * [ReviewUpdateInputForAdmin](#reviewupdateinputforadmin)
    * [ReviewWriteInput](#reviewwriteinput)
    * [ServiceManageUpdateInput](#servicemanageupdateinput)
    * [SignUpInput](#signupinput)
    * [SocialSignUpInput](#socialsignupinput)
    * [SortInput](#sortinput)
    * [StringFilterInput](#stringfilterinput)
    * [StringSortInput](#stringsortinput)
    * [UserAllowInput](#userallowinput)
    * [UserFCMTokenAddInput](#userfcmtokenaddinput)
    * [UserFilterInput](#userfilterinput)
    * [UserFilterInputForAdmin](#userfilterinputforadmin)
    * [UserNotificationSettingUpdateInput](#usernotificationsettingupdateinput)
    * [UserOrderInput](#userorderinput)
    * [UserProfileCompanyTypeUpdateInput](#userprofilecompanytypeupdateinput)
    * [UserProfileConsumerTypeUpdateInput](#userprofileconsumertypeupdateinput)
    * [UserProfileEngineerTypeUpdateInput](#userprofileengineertypeupdateinput)
    * [UserProfileUpdateInputForAdmin](#userprofileupdateinputforadmin)
    * [UserTypeFilterInput](#usertypefilterinput)
    * [UserTypeSortInput](#usertypesortinput)
    * [UserUpdateInput](#userupdateinput)
  * [Enums](#enums)
    * [AdminPostAction](#adminpostaction)
    * [AdminPostState](#adminpoststate)
    * [AdminPostType](#adminposttype)
    * [AdvertisementLocationEnum](#advertisementlocationenum)
    * [AdvertisementStateEnum](#advertisementstateenum)
    * [AnnouncementApplyStateEnum](#announcementapplystateenum)
    * [AnnouncementAttendanceStateEnum](#announcementattendancestateenum)
    * [AnnouncementFieldInfo](#announcementfieldinfo)
    * [AnnouncementOrderType](#announcementordertype)
    * [AnnouncementStateEnum](#announcementstateenum)
    * [AnnouncementWorkScopeEnum](#announcementworkscopeenum)
    * [AnnouncementWorkType](#announcementworktype)
    * [BooleanFilterOperators](#booleanfilteroperators)
    * [CRIPriorityEnum](#cripriorityenum)
    * [CategoryTypeEnum](#categorytypeenum)
    * [CommunityReportCategoryEnumType](#communityreportcategoryenumtype)
    * [CommunityReportStateEnumType](#communityreportstateenumtype)
    * [CommunityReportType](#communityreporttype)
    * [EnumFilterOperators](#enumfilteroperators)
    * [FcmTokenOsEnum](#fcmtokenosenum)
    * [IDFilterOperators](#idfilteroperators)
    * [InquireState](#inquirestate)
    * [InquireType](#inquiretype)
    * [MatchPostStateEnum](#matchpoststateenum)
    * [MyAnnouncementTabEnum](#myannouncementtabenum)
    * [NotificationStorageTargetType](#notificationstoragetargettype)
    * [NotificationType](#notificationtype)
    * [Nulls](#nulls)
    * [NumberFilterOperators](#numberfilteroperators)
    * [Order](#order)
    * [PaymentItemAuthEnum](#paymentitemauthenum)
    * [PaymentItemTypeEnum](#paymentitemtypeenum)
    * [PaymentMethodEnumType](#paymentmethodenumtype)
    * [PaymentRefundStateEnum](#paymentrefundstateenum)
    * [PaymentStateEnumType](#paymentstateenumtype)
    * [PointRefundStateEnum](#pointrefundstateenum)
    * [PointTypeEnum](#pointtypeenum)
    * [PortfolioConstructionTypeEnum](#portfolioconstructiontypeenum)
    * [PortfolioRecommendationStateEnum](#portfoliorecommendationstateenum)
    * [PortfolioServicePriceTypeEnum](#portfolioservicepricetypeenum)
    * [ProfilePerformanceTypeEnum](#profileperformancetypeenum)
    * [ProfileTypeEnum](#profiletypeenum)
    * [ReportCategoryEnumType](#reportcategoryenumtype)
    * [ReportStateEnumType](#reportstateenumtype)
    * [ReviewStateEnum](#reviewstateenum)
    * [SigunguTypeEnum](#sigungutypeenum)
    * [StringFilterOperators](#stringfilteroperators)
    * [UserRole](#userrole)
    * [UserSocialType](#usersocialtype)
    * [UserState](#userstate)
  * [Scalars](#scalars)
    * [Boolean](#boolean)
    * [DateTime](#datetime)
    * [Email](#email)
    * [Float](#float)
    * [ID](#id)
    * [Int](#int)
    * [JSON](#json)
    * [PhoneNumber](#phonenumber)
    * [String](#string)
  * [Interfaces](#interfaces)
    * [AdminPost](#adminpost)
    * [User](#user)
  * [Unions](#unions)
    * [CommunityReportTarget](#communityreporttarget)
    * [ProfileInfo](#profileinfo)

</details>

## Query
<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="query.file">file</strong></td>
<td valign="top"><a href="#file">File</a>!</td>
<td>

파일의 정보를 조회합니다.

**에러 코드**
- `NOT_FOUND`: 파일이 존재하지 않습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

파일 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.userdashboardforadmin">userDashboardForAdmin</strong></td>
<td valign="top"><a href="#userdashboardforadmin">UserDashboardForAdmin</a>!</td>
<td>

사이트 이용 분석

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.me">me</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

나 자신의 사용자를 조회합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.user">user</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

특정 사용자를 조회합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

사용자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.users">users</strong></td>
<td valign="top"><a href="#userlist">UserList</a>!</td>
<td>

사용자 목록을 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#userfilterinput">UserFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#userorderinput">UserOrderInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.usersforadmin">usersForAdmin</strong></td>
<td valign="top"><a href="#userlist">UserList</a>!</td>
<td>

유저 목록 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#userfilterinputforadmin">UserFilterInputForAdmin</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#userorderinput">UserOrderInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileType</td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

기업규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.profiledashboard">profileDashboard</strong></td>
<td valign="top"><a href="#profiledashboard">ProfileDashboard</a>!</td>
<td>

프로필 대시보드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.isduplicatecompanycode">isDuplicateCompanyCode</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

사업자등록번호 중복여부

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">code</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

사업자등록번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfoliorecommendations">portfolioRecommendations</strong></td>
<td valign="top">[<a href="#portfoliomodel">PortfolioModel</a>!]!</td>
<td>

포트폴리오 추천

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfolio">portfolio</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 단일 쿼리

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfolioforadmin">portfolioForAdmin</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 단일 쿼리 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfolios">portfolios</strong></td>
<td valign="top"><a href="#portfoliolist">PortfolioList</a>!</td>
<td>

포트폴리오 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#portfoliofilterinput">PortfolioFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#portfoliosortinput">PortfolioSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">input</td>
<td valign="top"><a href="#string">String</a></td>
<td>

검색어

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myportfolios">myPortfolios</strong></td>
<td valign="top"><a href="#portfoliolist">PortfolioList</a>!</td>
<td>

내 포트폴리오 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#portfoliofilterinput">PortfolioFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#portfoliosortinput">PortfolioSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myfavoriteportfolios">myFavoritePortfolios</strong></td>
<td valign="top"><a href="#portfoliolist">PortfolioList</a>!</td>
<td>

내가 관심 등록한 포트폴리오 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#portfoliofilterinput">PortfolioFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#portfoliosortinput">PortfolioSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfoliosforadmin">portfoliosForAdmin</strong></td>
<td valign="top"><a href="#portfoliolist">PortfolioList</a>!</td>
<td>

포트폴리오 리스트 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#portfoliofilterinput">PortfolioFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#portfoliosortinput">PortfolioSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.portfoliorecommendationsforadmin">portfolioRecommendationsForAdmin</strong></td>
<td valign="top"><a href="#portfoliorecommendationlist">PortfolioRecommendationList</a>!</td>
<td>

포트폴리오 추천 리스트 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#portfoliorecommendationfilterinput">PortfolioRecommendationFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#portfoliorecommendationsortinput">PortfolioRecommendationSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.pointsubscriptiondashboardforadmin">pointSubscriptionDashboardForAdmin</strong></td>
<td valign="top"><a href="#pointsubscriptiondashboardforadmin">PointSubscriptionDashboardForAdmin</a>!</td>
<td>

포인트 및 구독 대시보드 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">date</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

yyyyMMdd

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mypointinfo">myPointInfo</strong></td>
<td valign="top"><a href="#pointdashboard">PointDashboard</a>!</td>
<td>

내 포인트 현황

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mypoints">myPoints</strong></td>
<td valign="top"><a href="#pointlist">PointList</a>!</td>
<td>

내 포인트 내역 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#pointfilterinput">PointFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#pointsortinput">PointSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.pointsforadmin">pointsForAdmin</strong></td>
<td valign="top"><a href="#pointlist">PointList</a>!</td>
<td>

포인트 내역 조회 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#pointfilterinput">PointFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#pointsortinput">PointSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mypointrefundinfo">myPointRefundInfo</strong></td>
<td valign="top"><a href="#mypointrefundinfo">MyPointRefundInfo</a>!</td>
<td>

내 환급 진행 포인트 현황

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mypointrefunds">myPointRefunds</strong></td>
<td valign="top"><a href="#pointrefundlist">PointRefundList</a>!</td>
<td>

내 포인트 환전 신청 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#pointrefundfilterinput">PointRefundFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#pointrefundsortinput">PointRefundSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.pointrefundsforadmin">pointRefundsForAdmin</strong></td>
<td valign="top"><a href="#pointrefundlist">PointRefundList</a>!</td>
<td>

포인트 환전 신청 조회 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#pointrefundfilterinput">PointRefundFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#pointrefundsortinput">PointRefundSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.allpaymentitems">allPaymentItems</strong></td>
<td valign="top">[<a href="#paymentitemmodel">PaymentItemModel</a>!]!</td>
<td>

결제 항목 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">type</td>
<td valign="top"><a href="#paymentitemtypeenum">PaymentItemTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.allpaymentitemsforadmin">allPaymentItemsForAdmin</strong></td>
<td valign="top">[<a href="#paymentitemmodel">PaymentItemModel</a>!]!</td>
<td>

결제 항목 리스트 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.createpointitemforadmin">createPointItemForAdmin</strong></td>
<td valign="top"><a href="#paymentitemmodel">PaymentItemModel</a>!</td>
<td>

결제 항목 생성 - 관리자 권한, REGULAR_PAYMENT or SINGLE_PAYMENT type일 경우 point/freePoint는 0으로 고정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#paymentitemcreateinput">PaymentItemCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.updatepointitemforadmin">updatePointItemForAdmin</strong></td>
<td valign="top"><a href="#paymentitemmodel">PaymentItemModel</a>!</td>
<td>

결제 항목 수정 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#paymentitemupdateinput">PaymentItemUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.deletepointitemforadmin">deletePointItemForAdmin</strong></td>
<td valign="top"><a href="#paymentitemmodel">PaymentItemModel</a>!</td>
<td>

결제 항목 삭제 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.deletemanypointitemforadmin">deleteManyPointItemForAdmin</strong></td>
<td valign="top">[<a href="#paymentitemmodel">PaymentItemModel</a>!]!</td>
<td>

결제 항목 삭제 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myregularpayment">myRegularPayment</strong></td>
<td valign="top">[<a href="#subscriptionapplymodel">SubscriptionApplyModel</a>!]!</td>
<td>

현재 내가 구독중인 항목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.paymentsforadmin">paymentsForAdmin</strong></td>
<td valign="top"><a href="#paymentlist">PaymentList</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#paymentfilterinput">PaymentFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#paymentsortinput">PaymentSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mypaymentmethod">myPaymentMethod</strong></td>
<td valign="top"><a href="#paymentmethod">PaymentMethod</a>!</td>
<td>

나의 결제 수단

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.paymentrefunds">paymentRefunds</strong></td>
<td valign="top"><a href="#paymentrefundlist">PaymentRefundList</a>!</td>
<td>

관리자용 환불 리스트 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#paymentrefundfilterinput">PaymentRefundFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#paymentrefundsortinput">PaymentRefundSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementdashboardforadmin">announcementDashboardForAdmin</strong></td>
<td valign="top"><a href="#announcementdashboardforadminmodel">AnnouncementDashboardForAdminModel</a>!</td>
<td>

입찰모두찾기 - 관리자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myavailableannouncementdashboard">MyAvailableAnnouncementDashboard</strong></td>
<td valign="top"><a href="#myavailableannouncementdashboard">MyAvailableAnnouncementDashboard</a></td>
<td>

신청 가능한 입찰 대시보드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementdashboard">announcementDashboard</strong></td>
<td valign="top"><a href="#announcementdashboard">AnnouncementDashboard</a>!</td>
<td>

공고 대시보드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myannouncementdashboard">myAnnouncementDashboard</strong></td>
<td valign="top"><a href="#myannouncementdashboard">MyAnnouncementDashboard</a>!</td>
<td>

나의 공고 대시보드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcement">announcement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

공고 단일 정보

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcements">announcements</strong></td>
<td valign="top"><a href="#announcementlist">AnnouncementList</a>!</td>
<td>

공고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementfilterinput">AnnouncementFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementsortinput">AnnouncementSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">attendanceStateFilter</td>
<td valign="top">[<a href="#announcementattendancestateenum">AnnouncementAttendanceStateEnum</a>!]</td>
<td>

참여 상태

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">myAnnouncementTab</td>
<td valign="top"><a href="#myannouncementtabenum">MyAnnouncementTabEnum</a></td>
<td>

나의 입찰관리 탭

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">input</td>
<td valign="top"><a href="#string">String</a></td>
<td>

검색어 필터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myannouncements">myAnnouncements</strong></td>
<td valign="top"><a href="#announcementlist">AnnouncementList</a>!</td>
<td>

나의 공고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementfilterinput">AnnouncementFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementsortinput">AnnouncementSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementsforadmin">announcementsForAdmin</strong></td>
<td valign="top"><a href="#announcementlist">AnnouncementList</a>!</td>
<td>

공고 리스트 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementfilterinput">AnnouncementFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementsortinput">AnnouncementSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myfavoriteannouncements">myFavoriteAnnouncements</strong></td>
<td valign="top"><a href="#announcementlist">AnnouncementList</a>!</td>
<td>

내가 관심등록 한 공고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementfilterinput">AnnouncementFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementsortinput">AnnouncementSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementapply">announcementApply</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

입찰 참여 정보,본인 혹은 입찰 공고 작성자가 아니면 권한 없음

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementapplies">announcementApplies</strong></td>
<td valign="top"><a href="#announcementapplylist">AnnouncementApplyList</a>!</td>
<td>

입찰 참여 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementapplyfilterinput">AnnouncementApplyFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementapplysortinput">AnnouncementApplySortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementappliesforadmin">announcementAppliesForAdmin</strong></td>
<td valign="top"><a href="#announcementapplylist">AnnouncementApplyList</a>!</td>
<td>

입찰 참여 리스트 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementapplyfilterinput">AnnouncementApplyFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementapplysortinput">AnnouncementApplySortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementtemp">announcementTemp</strong></td>
<td valign="top"><a href="#announcementtempmodel">AnnouncementTempModel</a>!</td>
<td>

공고 단일 정보

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myannouncementtemps">myAnnouncementTemps</strong></td>
<td valign="top"><a href="#announcementtemplist">AnnouncementTempList</a>!</td>
<td>

나의 작성 중인 공고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#omitobjecttype">OmitObjectType</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementtempsortinput">AnnouncementTempSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">input</td>
<td valign="top"><a href="#string">String</a></td>
<td>

검색어

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.announcementtemps">announcementTemps</strong></td>
<td valign="top"><a href="#announcementtemplist">AnnouncementTempList</a>!</td>
<td>

공고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#announcementtempfilterinput">AnnouncementTempFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#announcementtempsortinput">AnnouncementTempSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.pageviews">pageViews</strong></td>
<td valign="top">[<a href="#pageviewsmodel">PageViewsModel</a>!]!</td>
<td>

방문자 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">startDate</td>
<td valign="top"><a href="#string">String</a></td>
<td>

YYYY-MM-DD

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">endDate</td>
<td valign="top"><a href="#string">String</a></td>
<td>

YYYY-MM-DD

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterprisedashboardforadmin">enterPriseDashboardForAdmin</strong></td>
<td valign="top"><a href="#enterprisedashboardmodel">EnterpriseDashboardModel</a>!</td>
<td>

업체 모두 찾기 보유 데이터 수 - 관리자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterprise">enterprise</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

프로필(업체) 정보

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterpriseforadmin">enterpriseForAdmin</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

프로필 조회 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterprises">enterprises</strong></td>
<td valign="top"><a href="#enterpriselist">EnterpriseList</a>!</td>
<td>

업체 리스트

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#enterprisefilterinput">EnterpriseFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#enterprisesortinput">EnterpriseSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">mainCategoryIds</td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

검색할 중분류 카테고리 id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subCategoryIds</td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

검색할 소분류 카테고리 id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderByDistance</td>
<td valign="top"><a href="#order">Order</a></td>
<td>

거리순 정렬

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">input</td>
<td valign="top"><a href="#string">String</a></td>
<td>

검색어 필터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterprisesforadmin">enterprisesForAdmin</strong></td>
<td valign="top"><a href="#enterpriselist">EnterpriseList</a>!</td>
<td>

업체 리스트 - 관리자권한

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#enterprisefilterinput">EnterpriseFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#enterprisesortinput">EnterpriseSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">categoryName</td>
<td valign="top"><a href="#string">String</a></td>
<td>

카테고리 필터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myviewenterprises">myViewEnterprises</strong></td>
<td valign="top"><a href="#enterpriselist">EnterpriseList</a>!</td>
<td>

업체 열람 리스트

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#enterprisefilterinput">EnterpriseFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#enterprisesortinput">EnterpriseSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myfavoriteenterprises">myFavoriteEnterprises</strong></td>
<td valign="top"><a href="#enterpriselist">EnterpriseList</a>!</td>
<td>

관심 등록한 업체 리스트

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#enterprisefilterinput">EnterpriseFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#enterprisesortinput">EnterpriseSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.categorycount">categoryCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

카테고리 개수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">parentId</td>
<td valign="top"><a href="#id">ID</a></td>
<td>

상위 뎁스 ID, 없을시 뎁스 1 리스트 반환

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.categories">categories</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]!</td>
<td>

업종 카테고리

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">parentId</td>
<td valign="top"><a href="#id">ID</a></td>
<td>

상위 뎁스 ID,없을시 뎁스1 리스트 반환

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.categoriesbyname">categoriesByName</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]!</td>
<td>

카테고리 이름으로 검색

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">name</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.categoriesforadmin">categoriesForAdmin</strong></td>
<td valign="top"><a href="#categorylist">CategoryList</a>!</td>
<td>

카테고리 리스트 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#categoryfilterinputforadmin">CategoryFilterInputForAdmin</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#categorysortinput">CategorySortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.financialfree">financialFree</strong></td>
<td valign="top"><a href="#financialmodel">FinancialModel</a></td>
<td>

재무/신용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.financialforadmin">financialForAdmin</strong></td>
<td valign="top"><a href="#financialmodel">FinancialModel</a></td>
<td>

총괄기업보고서 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.financial">financial</strong></td>
<td valign="top"><a href="#financialmodel">FinancialModel</a></td>
<td>

총괄기업보고서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myfinancial">myFinancial</strong></td>
<td valign="top"><a href="#financialmodel">FinancialModel</a></td>
<td>

나의 재무/신용등급/소송 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.companyinfosforadmin">companyInfosForAdmin</strong></td>
<td valign="top"><a href="#companyinfolist">CompanyInfoList</a>!</td>
<td>

화사 정보 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#companyinfofilterinput">CompanyInfoFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#companyinfosortinput">CompanyInfoSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.companyinfo">companyInfo</strong></td>
<td valign="top"><a href="#companyinfomodel">CompanyInfoModel</a></td>
<td>

사업자번호로 회사 정보 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">registrationNumber</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

사업자번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.licenses">licenses</strong></td>
<td valign="top"><a href="#licenselist">LicenseList</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#licensefilterinput">LicenseFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#licensesortinput">LicenseSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.cri">cri</strong></td>
<td valign="top"><a href="#crilist">CRIList</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#crifilterinput">CRIFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#crisortinput">CRISortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myblockusers">myBlockUsers</strong></td>
<td valign="top"><a href="#userblocklist">UserBlockList</a>!</td>
<td>

내가 차단한 사용자 목록을 조회합니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.unreadnotificationcnt">unReadNotificationCnt</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

본인이 읽지않은 알림 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.notification">notification</strong></td>
<td valign="top"><a href="#notification">Notification</a>!</td>
<td>

알림을 조회합니다. 관리자가 아닌 사용자는 자신의 알림만 조회할 수 있습니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

알림 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mynotifications">myNotifications</strong></td>
<td valign="top"><a href="#notificationlist">NotificationList</a>!</td>
<td>

내 알림 목록을 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#notificationfilterinput">NotificationFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#notificationsortinput">NotificationSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">unreadOnly</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

읽지 않음만 보기

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.notificationsforadmin">notificationsForAdmin</strong></td>
<td valign="top"><a href="#notificationlist">NotificationList</a>!</td>
<td>

전체 알림 목록을 가져옵니다. 관리자만 허용됩니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#notificationfilterinput">NotificationFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#notificationsortinput">NotificationSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.notificationstorage">notificationStorage</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

알림 저장소를 조회합니다. - 관리자 권한

**에러 코드**
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

알림 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.notificationstorages">notificationStorages</strong></td>
<td valign="top"><a href="#notificationstoragelist">NotificationStorageList</a>!</td>
<td>

알림 저장소 목록를 조회합니다. - 관리자 권한

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#notificationstoragefilterinput">NotificationStorageFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#notificationstoragesortinput">NotificationStorageSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.adminpost">adminPost</strong></td>
<td valign="top"><a href="#adminpost">AdminPost</a>!</td>
<td>

관리자가 작성한 게시물을 조회합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.adminposts">adminPosts</strong></td>
<td valign="top"><a href="#adminpostlist">AdminPostList</a>!</td>
<td>

관리자가 작성한 게시물 목록을 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#adminpostfilterinput">AdminPostFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#adminpostsortinput">AdminPostSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.adminpostcategories">adminPostCategories</strong></td>
<td valign="top">[<a href="#adminpostcategory">AdminPostCategory</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.inquireforadmin">inquireForAdmin</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 내용을 가져옵니다. - 관리자용

**에러 코드**
  - `NOT_FOUND`: 해당 문의를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

문의 아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.inquire">inquire</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 내용을 가져옵니다.

**에러 코드**
  - `NOT_FOUND`: 해당 문의를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

문의 아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.inquiresforadmin">inquiresForAdmin</strong></td>
<td valign="top"><a href="#inquirelist">InquireList</a>!</td>
<td>

문의 리스트를 가져옵니다. - 관리자용

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#inquirefilterinput">InquireFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#inquiresortinput">InquireSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myinquires">myInquires</strong></td>
<td valign="top"><a href="#inquirelist">InquireList</a>!</td>
<td>

내 문의 리스트를 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#inquirefilterinput">InquireFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#inquiresortinput">InquireSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.reportforadmin">reportForAdmin</strong></td>
<td valign="top"><a href="#report">Report</a>!</td>
<td>

특정 신고를 조회합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `NOT_FOUND`: 해당 신고 내역을 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

신고 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.reportsforadmin">reportsForAdmin</strong></td>
<td valign="top"><a href="#reportlist">ReportList</a>!</td>
<td>

전체 신고 내역을 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reportfilterinput">ReportFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reportsortinput">ReportSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myreports">myReports</strong></td>
<td valign="top"><a href="#reportlist">ReportList</a>!</td>
<td>

나의 전체 신고 내역을 가져옵니다.

[GraphQL Cursor Connections Specification](https://relay.dev/graphql/connections.htm)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reportfilterinput">ReportFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reportsortinput">ReportSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchpost">matchPost</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

매칭 게시물 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchposts">matchPosts</strong></td>
<td valign="top"><a href="#matchpostlist">MatchPostList</a>!</td>
<td>

매칭 게시물 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#matchpostfilterinput">MatchPostFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#matchpostorderbyinput">MatchPostOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchcategory">matchCategory</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a>!</td>
<td>

매칭 카테고리 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchcategories">matchCategories</strong></td>
<td valign="top"><a href="#matchpostcategorylist">MatchPostCategoryList</a>!</td>
<td>

매칭 카테고리 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#matchpostcategoryfilterinput">MatchPostCategoryFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#matchpostcategoryorderbyinput">MatchPostCategoryOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchposttype">matchPostType</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a>!</td>
<td>

매칭 게시물 타입 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.matchposttypes">matchPostTypes</strong></td>
<td valign="top"><a href="#matchposttypelist">MatchPostTypeList</a>!</td>
<td>

매칭 게시물 타입 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#matchposttypefilterinput">MatchPostTypeFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#matchposttypeorderbyinput">MatchPostTypeOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communitypostreply">communityPostReply</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communitypostreplies">communityPostReplies</strong></td>
<td valign="top"><a href="#communitypostreplylist">CommunityPostReplyList</a>!</td>
<td>

커뮤니티 게시물 댓글 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#communitypostreplyfilterinput">CommunityPostReplyFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#communitypostreplyorderbyinput">CommunityPostReplyOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communitycategory">communityCategory</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a>!</td>
<td>

커뮤니티 카테고리 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communitycategories">communityCategories</strong></td>
<td valign="top"><a href="#communitycategorylist">CommunityCategoryList</a>!</td>
<td>

커뮤니티 카테고리 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#communitycategoryfilterinput">CommunityCategoryFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#communitycategoryorderbyinput">CommunityCategoryOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communitypost">communityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communityposts">communityPosts</strong></td>
<td valign="top"><a href="#communitypostlist">CommunityPostList</a>!</td>
<td>

커뮤니티 게시물 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#communitypostfilterinput">CommunityPostFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#communitypostorderbyinput">CommunityPostOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communityreport">communityReport</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고 단일 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communityreportforadmin">communityReportForAdmin</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고 단일 조회 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.communityreportsforadmin">communityReportsForAdmin</strong></td>
<td valign="top"><a href="#communityreportlist">CommunityReportList</a>!</td>
<td>

커뮤니티 신고 목록 조회 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#communityreportfilterinput">CommunityReportFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#communityreportorderbyinput">CommunityReportOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mycommunityreports">myCommunityReports</strong></td>
<td valign="top"><a href="#communityreportlist">CommunityReportList</a>!</td>
<td>

내 커뮤니티 신고 목록 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#communityreportfilterinput">CommunityReportFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#communityreportorderbyinput">CommunityReportOrderByInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.servicemanage">serviceManage</strong></td>
<td valign="top"><a href="#servicemanage">ServiceManage</a>!</td>
<td>

서비스 운영 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.myreviewdashboard">myReviewDashboard</strong></td>
<td valign="top"><a href="#myreviewdashboard">MyReviewDashboard</a>!</td>
<td>

내가 받은 리뷰 대시보드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.reviewdashboard">reviewDashboard</strong></td>
<td valign="top"><a href="#myreviewdashboard">MyReviewDashboard</a>!</td>
<td>

특정 업체의 리뷰 대시보드

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.review">review</strong></td>
<td valign="top"><a href="#reviewmodel">ReviewModel</a>!</td>
<td>

리뷰 단일

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.reviews">reviews</strong></td>
<td valign="top"><a href="#reviewlist">ReviewList</a>!</td>
<td>

리뷰 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reviewfilterinput">ReviewFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reviewsortinput">ReviewSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.enterprisereviews">enterpriseReviews</strong></td>
<td valign="top"><a href="#reviewlist">ReviewList</a>!</td>
<td>

특정 기업의 리뷰 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">profileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reviewfilterinput">ReviewFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reviewsortinput">ReviewSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.mywritereviews">myWriteReviews</strong></td>
<td valign="top"><a href="#reviewlist">ReviewList</a>!</td>
<td>

내가 쓴 리뷰 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reviewfilterinput">ReviewFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reviewsortinput">ReviewSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.reviewsforadmin">reviewsForAdmin</strong></td>
<td valign="top"><a href="#reviewlist">ReviewList</a>!</td>
<td>

리뷰 리스트 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reviewfilterinputforadmin">ReviewFilterInputForAdmin</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reviewsortinput">ReviewSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.receivedreviews">receivedReviews</strong></td>
<td valign="top"><a href="#reviewlist">ReviewList</a>!</td>
<td>

내가 받은 리뷰 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#reviewfilterinput">ReviewFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#reviewsortinput">ReviewSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.sigungulist">sigunguList</strong></td>
<td valign="top">[<a href="#sigungumodel">SigunguModel</a>!]!</td>
<td>

시군구 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">si</td>
<td valign="top"><a href="#string">String</a></td>
<td>

필터링할 시 명 없을시 시 데이터만 반환

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">keyword</td>
<td valign="top"><a href="#string">String</a></td>
<td>

검색할 시군구명, 해당 값이 존재시 다른 args는 무시됩니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.advertisements">advertisements</strong></td>
<td valign="top">[<a href="#advertisementmodel">AdvertisementModel</a>!]</td>
<td>

광고 (무작위로 두개 리턴됩니다.)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.advertisementforadmin">advertisementForAdmin</strong></td>
<td valign="top"><a href="#advertisementmodel">AdvertisementModel</a>!</td>
<td>

관리자용 광고 조회

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.advertisementsforadmin">advertisementsForAdmin</strong></td>
<td valign="top"><a href="#advertisementlist">AdvertisementList</a>!</td>
<td>

관리자용 광고 리스트

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#advertisementfilterinput">AdvertisementFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#advertisementsortinput">AdvertisementSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.bankcode">bankCode</strong></td>
<td valign="top"><a href="#bankcodemodel">BankCodeModel</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.bankcodes">bankCodes</strong></td>
<td valign="top"><a href="#bankcodelist">BankCodeList</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">filter</td>
<td valign="top">[<a href="#bankcodefilterinput">BankCodeFilterInput</a>!]</td>
<td>

필터링할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sort</td>
<td valign="top">[<a href="#bankcodesortinput">BankCodeSortInput</a>!]</td>
<td>

정렬할 요소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

앞에서부터 가져올 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">last</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

뒤에서부터 가져졸 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">after</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디부터 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">before</td>
<td valign="top"><a href="#string">String</a></td>
<td>

어디까지 기준인지 설정할 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">offset</td>
<td valign="top"><a href="#int">Int</a></td>
<td>

건너뛸 데이터 개 수 (OFFSET)

</td>
</tr>
</tbody>
</table>

## Mutation
<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signin">signIn</strong></td>
<td valign="top"><a href="#authtokenresponse">AuthTokenResponse</a>!</td>
<td>

사용자 이름(아이디)으로 로그인합니다.

**에러 목록**
- `UNAUTHENTICATED`: 아이디 또는 비밀번호가 틀렸습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">loginId</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

로그인 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">password</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

비밀번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.isexistemail">isExistEmail</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

이메일이 존재하는지 여부

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">email</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signup">signUp</strong></td>
<td valign="top"><a href="#signupresult">SignUpResult</a>!</td>
<td>

회원가입하여 사용자를 생성합니다. email 또는 name이 반드시 있어야합니다.

**에러 목록**
- `BAD_USER_INPUT` (EMAIL_OR_NAME_REQUIRED): email 또는 name이 반드시 있어야합니다.
- `BAD_USER_INPUT`: 데이터 유효성 검증 에러

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#signupinput">SignUpInput</a>!</td>
<td>

회원가입 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">requestId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isMarketingNoti</td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

마케팅 수신여부

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isAllowGeolocation</td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

위치기반서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isAllowThirdParty</td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

제3자 정보제공 동의

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isAllowKakaotalk</td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

카카오톡 알림 수신 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateme">updateMe</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

나 자신의 사용자 정보를 수정합니다.

**에러 코드**
- FORBIDDEN: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userupdateinput">UserUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.wakeupsleeper">wakeUpSleeper</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

나의 휴면 상태를 해제합니다.

**에러 코드**
- NOT_FOUND: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.leavinguser">leavingUser</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

탈퇴 처리
**에러 코드**
- NOT_FOUND: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateuseradminmemo">updateUserAdminMemo</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

특정 유저의 관리자 메모를 변경합니다.

**에러 코드**
- `NOT_FOUND`: 없는 유저.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

유저 아이디

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">memo</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

메모 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.leavinguserforadmin">leavingUserForAdmin</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

특정 유저를 탈퇴처리합니다.

**에러 코드**
- `NOT_FOUND`: 없는 유저.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

유저 아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.suspenduser">suspendUser</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

특정 유저를 정지처리합니다.

**에러 코드**
- `NOT_FOUND`: 없는 유저.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

유저 아이디

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">suspendedEndAt</td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

정지 종료날

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">suspendedReason</td>
<td valign="top"><a href="#string">String</a></td>
<td>

정지 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateuserforadmin">updateUserForAdmin</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

유저 정보 변경 - 관리자 권한

  **에러 코드**
- `NOT_FOUND`: 없는 유저.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

유저 아이디

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userupdateinput">UserUpdateInput</a>!</td>
<td>

변경할 유저 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.wakeupsleeperforadmin">wakeUpSleeperForAdmin</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

휴면 상태를 해제합니다.

**에러 코드**
- NOT_FOUND: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

유저 아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteprofileforadmin">deleteProfileForAdmin</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

프로필 삭제 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateprofileforadmin">updateProfileForAdmin</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

프로필 수정 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userprofileupdateinputforadmin">UserProfileUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateprofilecorporationtype">updateProfileCorporationType</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

법인 프로필 정보 수정, 요청시 프로필 type이 변경됩니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userprofilecompanytypeupdateinput">UserProfileCompanyTypeUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">progress</td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isNiceCertified</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateprofileprivatebusinesstype">updateProfilePrivateBusinessType</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

개인 사업자 프로필 정보 수정, 요청시 프로필 type이 변경됩니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userprofilecompanytypeupdateinput">UserProfileCompanyTypeUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">progress</td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isNiceCertified</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateprofileengineertype">updateProfileEngineerType</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

기술자 프로필 정보 수정, 요청시 프로필 type이 변경됩니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userprofileengineertypeupdateinput">UserProfileEngineerTypeUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">progress</td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateprofileconsumertype">updateProfileConsumerType</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

일반 소비자 프로필 정보 수정, 요청시 프로필 type이 변경됩니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userprofileconsumertypeupdateinput">UserProfileConsumerTypeUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">progress</td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.refreshtoken">refreshToken</strong></td>
<td valign="top"><a href="#authtokenresponse">AuthTokenResponse</a>!</td>
<td>

갱신 토큰으로 토큰을 새로 발급받습니다. 갱신 토큰도 일정 기간이 지난 경우에는 새로 발급됩니다.

**에러 코드**
- `UNAUTHENTICATED`: 만료된 갱신 토큰입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">refreshToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

갱신 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createportfolio">createPortfolio</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#portfoliocreateinput">PortfolioCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateportfolio">updatePortfolio</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#portfolioupdateinput">PortfolioUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteportfolio">deletePortfolio</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateportfolioforadmin">updatePortfolioForAdmin</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 수정 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#portfolioupdateinputforadmin">PortfolioUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteportfolioforadmin">deletePortfolioForAdmin</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 삭제 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addportfoliofavorite">addPortfolioFavorite</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 관심등록

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteportfoliofavorite">deletePortfolioFavorite</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

포트폴리오 관심등록 취소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createportfoliorecommendation">createPortfolioRecommendation</strong></td>
<td valign="top"><a href="#portfoliorecommendationmodel">PortfolioRecommendationModel</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#portfoliorecommendationcreateinput">PortfolioRecommendationCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateportfoliorecommendation">updatePortfolioRecommendation</strong></td>
<td valign="top"><a href="#portfoliorecommendationmodel">PortfolioRecommendationModel</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#portfoliorecommendationupdateinput">PortfolioRecommendationUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteportfoliorecommendation">deletePortfolioRecommendation</strong></td>
<td valign="top"><a href="#portfoliorecommendationmodel">PortfolioRecommendationModel</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.reqpointrefund">reqPointRefund</strong></td>
<td valign="top"><a href="#point">Point</a>!</td>
<td>

포인트 환전 신청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#pointrefundcreateinput">PointRefundCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.allowpointrefund">allowPointRefund</strong></td>
<td valign="top"><a href="#pointrefund">PointRefund</a>!</td>
<td>

포인트 환전 신청 수락 - 관리자권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.rejectpointrefund">rejectPointRefund</strong></td>
<td valign="top"><a href="#pointrefund">PointRefund</a>!</td>
<td>

포인트 환전 신청 거절 - 관리자권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">reason</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

거절 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.cancelregularpayment">cancelRegularPayment</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내 구독 취소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createsubscription">createSubscription</strong></td>
<td valign="top"><a href="#subscriptionapplymodel">SubscriptionApplyModel</a>!</td>
<td>

구독 신청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">itemId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

구독할 항목 id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">paymentMethodId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

결제 수단 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createorder">createOrder</strong></td>
<td valign="top"><a href="#paymentresponsemodel">PaymentResponseModel</a>!</td>
<td>

포인트 구매

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">itemId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.requestorderconfirm">requestOrderConfirm</strong></td>
<td valign="top"><a href="#paymentmodel">PaymentModel</a>!</td>
<td>

주문 승인 요청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">moid</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주문번호

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">transactionId</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

PG사에서 발급한 거래번호

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">token</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

인증 token

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">nextAppURL</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

승인 요청 url

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">netCancelURL</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

망취소 요청 url

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">signature</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

위변조 검증 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">payMethod</td>
<td valign="top"><a href="#paymentmethodenumtype">PaymentMethodEnumType</a></td>
<td>

결제 수단

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatepaymentforadmin">updatePaymentForAdmin</strong></td>
<td valign="top"><a href="#paymentmodel">PaymentModel</a>!</td>
<td>

구매 내역 수정 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

payment id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#paymentupdateinputforadmin">PaymentUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createpaymentmethod">createPaymentMethod</strong></td>
<td valign="top"><a href="#paymentmethod">PaymentMethod</a>!</td>
<td>

결제 수단 등록

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#paymentmethodcreateinput">PaymentMethodCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletepaymentmethod">deletePaymentMethod</strong></td>
<td valign="top"><a href="#paymentmethod">PaymentMethod</a>!</td>
<td>

결제 수단 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatepaymentrefundstateforadmin">updatePaymentRefundStateForAdmin</strong></td>
<td valign="top"><a href="#paymentrefundmodel">PaymentRefundModel</a>!</td>
<td>

환불 승인/거절 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

paymentRefundId

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">state</td>
<td valign="top"><a href="#paymentrefundstateenum">PaymentRefundStateEnum</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createpaymentrefund">createPaymentRefund</strong></td>
<td valign="top"><a href="#paymentrefundmodel">PaymentRefundModel</a>!</td>
<td>

환불 요청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">paymentId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

payment id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.sendannouncementalimtalkbycategory">sendAnnouncementAlimtalkByCategory</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

관심 업종 입찰 공고 알림톡 보내기 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">categoryIds</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

업종 카테고리 id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">url</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

알림톡 클릭시 이동할 url

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.sendannouncementalimtalkbyaddress">sendAnnouncementAlimtalkByAddress</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

관심 지역 입찰 공고 알림톡 보내기 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">sido</td>
<td valign="top">[<a href="#string">String</a>!]!</td>
<td>

행정구역의 시, 도

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">url</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

알림톡 클릭시 이동할 url

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteannouncementforadmin">deleteAnnouncementForAdmin</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

공고 삭제 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateannouncementforadmin">updateAnnouncementForAdmin</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

공고 수정 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementupdateinputforadmin">AnnouncementUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createannouncement">createAnnouncement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰 공사 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementcreateinput">AnnouncementCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">tempId</td>
<td valign="top"><a href="#id">ID</a></td>
<td>

삭제항 입찰 공사 임시 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.recreateannouncement">reCreateAnnouncement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰 공사 재생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a></td>
<td>

재성성할 입찰 공사 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateannouncement">updateAnnouncement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰 공고 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementupdateinput">AnnouncementUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addannouncementfavorite">addAnnouncementFavorite</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰공고 관심등록

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteannouncementfavorite">deleteAnnouncementFavorite</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰공고 관심등록 취소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.applyannouncement">applyAnnouncement</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

입찰 참여하기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">announcementId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

공고 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.submitannouncementapply">submitAnnouncementApply</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

입찰 참여 신청서 제출

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

입찰에 참여 후 발급받은 id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementapplycreateinput">AnnouncementApplyCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.selectedannouncementapply">selectedAnnouncementApply</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

입찰 참여 선정하기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">applyId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.giveupannouncementapply">giveUpAnnouncementApply</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

입찰 포기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">announcementId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteannouncementapplyestimatefiles">deleteAnnouncementApplyEstimateFiles</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

입찰 견적서 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createannouncementtemp">createAnnouncementTemp</strong></td>
<td valign="top"><a href="#announcementtempmodel">AnnouncementTempModel</a>!</td>
<td>

입찰 공사 임시 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementtempcreateinput">AnnouncementTempCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateannouncementtemp">updateAnnouncementTemp</strong></td>
<td valign="top"><a href="#announcementtempmodel">AnnouncementTempModel</a>!</td>
<td>

임시 입찰 공고 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#announcementtempupdateinput">AnnouncementTempUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteannouncementtemp">deleteAnnouncementTemp</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

임시 입찰 공고 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteenterpriseviewlog">deleteEnterpriseViewLog</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

프로필 열람 기록 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addenterprisefavorite">addEnterpriseFavorite</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

업체 관심등록

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteenterprisefavorite">deleteEnterpriseFavorite</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

업체 관심등록 취소

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.uploadcategoryexcel">uploadCategoryExcel</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]!</td>
<td>

카테고리 엑셀 업로드 (형식은 카테고리 엑셀 다운로드 파일)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createcategoryforadmin">createCategoryForAdmin</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a>!</td>
<td>

카테고리 추가 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#categorycreateinputforadmin">CategoryCreateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecategoryforadmin">updateCategoryForAdmin</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a>!</td>
<td>

카테고리 수정 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#categoryupdateinputforadmin">CategoryUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecategoryforadmin">deleteCategoryForAdmin</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a>!</td>
<td>

카테고리 삭제 - 관리자

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.insertcompanyinfofromexcel">insertCompanyInfoFromExcel</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

사업자정보 엑셀로 업로드(이미 정보가 존재한다면 update, 없으면 insert)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fileId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

업로드한 엑셀 파일의 fileId

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.blockuser">blockUser</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

사용자를 차단하거나 해제합니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isBlocking</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">userId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.blockusers">blockUsers</strong></td>
<td valign="top">[<a href="#member">Member</a>!]!</td>
<td>

사용자들을 차단하거나 해제합니다.
이미 차단 혹은 해제된 상태이면 무시합니다.
반환값은 처리된 userIds의 정보입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isBlocking</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">userIds</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.setfcmtoken">setFCMToken</strong></td>
<td valign="top"><a href="#userfcmtoken">UserFCMToken</a>!</td>
<td>

나 자신의 사용자에게 FCM 토큰을 추가합니다. 이미 추가된 적이 있는 토큰인 경우, 시간 갱신만 이루어집니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#userfcmtokenaddinput">UserFCMTokenAddInput</a>!</td>
<td>

FCM 토큰 추가 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.removefcmtoken">removeFCMToken</strong></td>
<td valign="top"><a href="#userfcmtoken">UserFCMToken</a>!</td>
<td>

추가되있는 FCM 토큰을 삭제합니다. 내가 추가한 FCM 토큰만 가능합니다.

**에러 코드**
- `NOT_FOUND`: 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fcmRegistrationToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

FCM 등록 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.sendnotificationforadmin">sendNotificationForAdmin</strong></td>
<td valign="top"><a href="#notification">Notification</a>!</td>
<td>

임의 알림을 생성합니다. 관리자만 허용됩니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#notificationcreateinput">NotificationCreateInput</a>!</td>
<td>

알림 생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.readnotification">readNotification</strong></td>
<td valign="top"><a href="#notification">Notification</a>!</td>
<td>

특정 알림을 읽음 처리합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

알림 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.readallnotification">readAllNotification</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

모든 알림을 읽음 처리합니다.

읽음처리한 개수를 반환

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createnotificationstoreforadmin">createNotificationStoreForAdmin</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

알림 저장소를 생성합니다 - 관리자 권한

**에러 코드**
- `BAD_REQUEWST`: SPECIFIC은 recipient_ids가 필수 입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#notificationstoragecreateinput">NotificationStorageCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isSend</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

즉시 전송 여부

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">recipient_ids</td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

target이 SPECIFIC일때 필수이며, 그 외는 무시됩니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatenotificationstoreforadmin">updateNotificationStoreForAdmin</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

알림 저장소를 수정합니다 - 관리자 권한

**에러 코드**
- `BAD_REQUEWST`: SPECIFIC은 recipient_ids가 필수 입니다.
- `BAD_REQUEWST`: 이미 전송된 알림입니다.
- `NOT_FOUND`: 없는 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

아이디

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#notificationstorageupdateinput">NotificationStorageUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">recipient_ids</td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

target이 SPECIFIC일때 필수이며, 그 외는 무시됩니다.

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletenotificationstoreforadmin">deleteNotificationStoreForAdmin</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

알림 저장소를 삭제합니다 - 관리자 권한

**에러 코드**
- `BAD_REQUEWST`: 이미 전송된 알림입니다.
- `NOT_FOUND`: 없는 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.sendnotificationstoreforadmin">sendNotificationStoreForAdmin</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

알림 저장소에 해당하는 알림을 전송합니다 - 관리자 권한

**에러 코드**
- `BAD_REQUEWST`: 이미 전송된 알림입니다.
- `NOT_FOUND`: 없는 데이터

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createnoticeforadmin">createNoticeForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

공지사항을 생성합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#noticecreateinput">NoticeCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatenoticeforadmin">updateNoticeForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

공지사항을 수정합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#noticeupdateinput">NoticeUpdateInput</a>!</td>
<td>

수정할 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletenoticeforadmin">deleteNoticeForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

공지사항을 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createfaqforadmin">createFaqForAdmin</strong></td>
<td valign="top"><a href="#faq">Faq</a>!</td>
<td>

자주 묻는 질문을 생성합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#faqcreateinput">FaqCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatefaqforadmin">updateFaqForAdmin</strong></td>
<td valign="top"><a href="#faq">Faq</a>!</td>
<td>

자주 묻는 질문을 수정합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#faqupdateinput">FaqUpdateInput</a>!</td>
<td>

수정할 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletefaqforadmin">deleteFaqForAdmin</strong></td>
<td valign="top"><a href="#faq">Faq</a>!</td>
<td>

자주 묻는 질문을 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletefaqsforadmin">deleteFaqsForAdmin</strong></td>
<td valign="top">[<a href="#faq">Faq</a>!]!</td>
<td>

자주 묻는 질문을 여러 개 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

게시물 ID 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createbannerforadmin">createBannerForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

배너를 생성합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#bannercreateinput">BannerCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatebannerforadmin">updateBannerForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

배너를 수정합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#bannerupdateinput">BannerUpdateInput</a>!</td>
<td>

수정할 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletebannerforadmin">deleteBannerForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

배너를 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createpopupforadmin">createPopupForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

팝업을 생성합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#popupcreateinput">PopupCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatepopupforadmin">updatePopupForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

팝업을 수정합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#popupupdateinput">PopupUpdateInput</a>!</td>
<td>

수정할 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletepopupforadmin">deletePopupForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

팝업을 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createeventforadmin">createEventForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

이벤트를 생성합니다. 관리자만 허용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#eventcreateinput">EventCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateeventforadmin">updateEventForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

이벤트를 수정합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#eventupdateinput">EventUpdateInput</a>!</td>
<td>

수정할 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteeventforadmin">deleteEventForAdmin</strong></td>
<td valign="top"><a href="#notice">Notice</a>!</td>
<td>

이벤트를 삭제합니다. 관리자만 허용합니다.

**에러 코드**
- `NOT_FOUND`: 해당 게시물을 찾을 수 없습니다.
- `FORBIDDEN`: 권한이 없습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

게시물 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createadminpostcategory">createAdminPostCategory</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#adminpostcategorycreateinput">AdminPostCategoryCreateInput</a>!</td>
<td>

생성 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateadminpostcategory">updateAdminPostCategory</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#adminpostcategoryupdateinput">AdminPostCategoryUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteadminpostcategory">deleteAdminPostCategory</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createinquire">createInquire</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 생성하기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#inquirecreateinput">InquireCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateinquire">updateInquire</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 수정하기

**에러 코드**
- `NOT_FOUND`: 존재하지 않는 문의입니다.
- `BAD_REQUEST`: 수정이 불가능한 상태입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#inquireupdateinput">InquireUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteinquire">deleteInquire</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 삭제하기

**에러 코드**
- `NOT_FOUND`: 존재하지 않는 문의입니다.
- `BAD_REQUEST`: 삭제가 불가능한 상태입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateinquireforadmin">updateInquireForAdmin</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 수정하기 - 관리자용

**에러 코드**
- `NOT_FOUND`: 존재하지 않는 문의입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#inquireupdateinputforadmin">InquireUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.answerinquireforadmin">answerInquireForAdmin</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 답변하기 - 관리자용

**에러 코드**
- `NOT_FOUND`: 존재하지 않는 문의입니다.
- `BAD_REQUEST` : 이미 답변한 문의입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">answerContent</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

답변 내용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isPush</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

문의자에게 푸시 전송 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.changeinquirestateforadmin">changeInquireStateForAdmin</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

문의 상태변경하기 - 관리자용

**에러 코드**
- `NOT_FOUND`: 존재하지 않는 문의입니다.
- `BAD_REQUEST` : 이미 답변한 문의입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">state</td>
<td valign="top"><a href="#inquirestate">InquireState</a>!</td>
<td>

변경할 상태

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isPush</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

문의자에게 푸시 전송 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createreport">createReport</strong></td>
<td valign="top"><a href="#report">Report</a>!</td>
<td>

신고를 생성합니다. 사용자가 신고 기능을 사용하고 싶을 때 사용합니다.

**에러 코드**
- `FORBIDDEN`: 권한이 없습니다.
- `BAD_USER_INPUT`: 신고 내용은 500자 이하로 입력해주세요.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#reportcreateinput">ReportCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatereportforadmin">updateReportForAdmin</strong></td>
<td valign="top"><a href="#report">Report</a>!</td>
<td>

신고 내역 단일 수정 (파일 수정 제외)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

신고 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#reportupdateinput">ReportUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatemanyreportforadmin">updateManyReportForAdmin</strong></td>
<td valign="top">[<a href="#report">Report</a>!]!</td>
<td>

복수 신고 내역 일괄 수정 (파일 수정 제외)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

신고 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#reportupdateinput">ReportUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletereportforadmin">deleteReportForAdmin</strong></td>
<td valign="top"><a href="#report">Report</a>!</td>
<td>

신고 내역 단일 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

report uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletemanyreportsforadmin">deleteManyReportsForAdmin</strong></td>
<td valign="top">[<a href="#report">Report</a>!]!</td>
<td>

신고 내역 복수 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

report uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatematchpostfiles">updateMatchPostFiles</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

매칭 게시물 파일 변경

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fileIds</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.incrementmatchpostviewcount">incrementMatchPostViewCount</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

매칭 게시물 조회수 +1

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addmatchpostlike">addMatchPostLike</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

매칭 게시물 좋아요

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletematchpostlike">deleteMatchPostLike</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

매칭 게시물 좋아요 취소(제거)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.creatematchpostcategorybyadmin">createMatchPostCategoryByAdmin</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a>!</td>
<td>

매칭 카테고리 생성 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#matchpostcategorycreateinput">MatchPostCategoryCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatematchpostcategorybyadmin">updateMatchPostCategoryByAdmin</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a>!</td>
<td>

매칭 카테고리 단일 수정 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#matchpostcategoryupdateinput">MatchPostCategoryUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletematchpostcategorybyadmin">deleteMatchPostCategoryByAdmin</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a>!</td>
<td>

매칭 카테고리 단일 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletematchcategoriesbyadmin">deleteMatchCategoriesByAdmin</strong></td>
<td valign="top">[<a href="#matchpostcategory">MatchPostCategory</a>!]!</td>
<td>

매칭 카테고리 복수 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.creatematchposttypeforadmin">createMatchPostTypeForAdmin</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a>!</td>
<td>

매칭 게시물 타입 생성 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#matchposttypecreateinput">MatchPostTypeCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatematchposttypeforadmin">updateMatchPostTypeForAdmin</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a>!</td>
<td>

매칭 게시물 타입 단일 수정 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#matchposttypeupdateinput">MatchPostTypeUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletematchposttypeforadmin">deleteMatchPostTypeForAdmin</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a>!</td>
<td>

매칭 게시물 타입 단일 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletematchposttypesforadmin">deleteMatchPostTypesForAdmin</strong></td>
<td valign="top">[<a href="#matchposttype">MatchPostType</a>!]!</td>
<td>

매칭 게시물 타입 복수 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createcommunitypostreply">createCommunityPostReply</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitypostreplycreateinput">CommunityPostReplyCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunitypostreply">updateCommunityPostReply</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitypostreplyupdateinput">CommunityPostReplyUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypostreply">deleteCommunityPostReply</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 단일 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletemanycommunitypostrepliesforadmin">deleteManyCommunityPostRepliesForAdmin</strong></td>
<td valign="top">[<a href="#communitypostreply">CommunityPostReply</a>!]!</td>
<td>

커뮤니티 게시물 댓글 복수 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addcommunitypostreplylike">addCommunityPostReplyLike</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 좋아요

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypostreplylike">deleteCommunityPostReplyLike</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 좋아요 취소(제거)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createcommunitycategoryforadmin">createCommunityCategoryForAdmin</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a>!</td>
<td>

커뮤니티 카테고리 생성 - 관리자 권한

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitycategorycreateinput">CommunityCategoryCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunitycategoryforadmin">updateCommunityCategoryForAdmin</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a>!</td>
<td>

커뮤니티 카테고리 단일 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitycategoryupdateinput">CommunityCategoryUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitycategoryforadmin">deleteCommunityCategoryForAdmin</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a>!</td>
<td>

커뮤니티 카테고리 단일 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitycategoriesforadmin">deleteCommunityCategoriesForAdmin</strong></td>
<td valign="top">[<a href="#communitycategory">CommunityCategory</a>!]!</td>
<td>

커뮤니티 카테고리 복수 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addcommunitycategoryfavorite">addCommunityCategoryFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 카테고리 즐겨찾기 추가

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">communityCategoryId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

커뮤니티 카테고리 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitycategoryfavorite">deleteCommunityCategoryFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 카테고리 즐겨찾기에서 제거

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">communityCategoryId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

커뮤니티 카테고리 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createcommunitypost">createCommunityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitypostcreateinput">CommunityPostCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunitypost">updateCommunityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communitypostupdateinput">CommunityPostUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunitypostfiles">updateCommunityPostFiles</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 파일 변경

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fileIds</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.incrementcommunitypostviewcount">incrementCommunityPostViewCount</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 조회수 +1

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypost">deleteCommunityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 단일 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypostsforadmin">deleteCommunityPostsForAdmin</strong></td>
<td valign="top">[<a href="#communitypost">CommunityPost</a>!]!</td>
<td>

커뮤니티 게시물 복수 삭제 관리자 전용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.pincommunitypostsforadmin">pinCommunityPostsForAdmin</strong></td>
<td valign="top">[<a href="#communitypost">CommunityPost</a>!]!</td>
<td>

커뮤니티 게시물 상단 고정 관리자 전용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">ids</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">isPinned</td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

상단 고정 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addcommunitypostlike">addCommunityPostLike</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 좋아요

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypostlike">deleteCommunityPostLike</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 좋아요 취소(제거)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addcommunityposthide">addCommunityPostHide</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 숨기기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunityposthide">deleteCommunityPostHide</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 숨기기 취소(제거)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.addcommunitypostfavorite">addCommunityPostFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 게시글 즐겨찾기 추가

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">postId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

커뮤니티 카테고리 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunitypostfavorite">deleteCommunityPostFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 게시글 즐겨찾기에서 제거

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">postId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

커뮤니티 게시글 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createcommunityreport">createCommunityReport</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고 생성

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communityreportcreateinput">CommunityReportCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunityreport">updateCommunityReport</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 게시물 수정

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#communityreportupdateinput">CommunityReportUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunityreportfiles">updateCommunityReportFiles</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고물 파일 변경

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">fileIds</td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletecommunityreport">deleteCommunityReport</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고 단일 삭제

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatecommunityreportforadmin">updateCommunityReportForAdmin</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

커뮤니티 신고 변경 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">state</td>
<td valign="top"><a href="#communityreportstateenumtype">CommunityReportStateEnumType</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">adminMemo</td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자 메모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.requestauthnumber">requestAuthNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호 인증 요청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">phoneNumber</td>
<td valign="top"><a href="#phonenumber">PhoneNumber</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.validateauthnumber">validateAuthNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

전화번호 인증 확인

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">phoneNumber</td>
<td valign="top"><a href="#phonenumber">PhoneNumber</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">authNumber</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.finduserbyphone">findUserByPhone</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

휴대폰 번호로 유저가 존재하는지 체크
휴대폰 인증처리가된 휴대폰 번호와 고유 코드가 필요

**에러 코드**
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.
- `BAD_REQUEST`: 잘못된 요청 혹은 인증 시간이 초과되었습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">name</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">phoneNumber</td>
<td valign="top"><a href="#phonenumber">PhoneNumber</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">requestId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.changepasswordfromphoneauth">changePasswordFromPhoneAuth</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

휴대폰 번호로 유저 비밀번호 변경
휴대폰 인증처리가된 휴대폰 번호와 고유 코드가 필요

**에러 코드**
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.
- `BAD_REQUEST`: 잘못된 요청 혹은 인증 시간이 초과되었습니다.
- `BAD_REQUEST`: 소셜로 가입된 계정입니다
- `BAD_REQUEST`: 비밀번호 변경이 불가한 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">email</td>
<td valign="top"><a href="#email">Email</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">phoneNumber</td>
<td valign="top"><a href="#phonenumber">PhoneNumber</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">requestId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">newPassword</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

새로운 비밀번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.validatefindemailphoneauth">validateFindEmailPhoneAuth</strong></td>
<td valign="top"><a href="#finedaccount">FinedAccount</a>!</td>
<td>

휴대폰 인증으로 휴대폰 번호로 가입된 유저의 loginId 반환
휴대폰 인증처리가된 휴대폰 번호와 고유 코드가 필요

**에러 코드**
- `NOT_FOUND`: 해당 사용자를 찾을 수 없습니다.
- `BAD_REQUEST`: 잘못된 요청 혹은 인증 시간이 초과되었습니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">name</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">phoneNumber</td>
<td valign="top"><a href="#phonenumber">PhoneNumber</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">requestId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateservicemanage">updateServiceManage</strong></td>
<td valign="top"><a href="#servicemanage">ServiceManage</a>!</td>
<td>

서비스 운영 정보 수정 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#servicemanageupdateinput">ServiceManageUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updatereviewforadmin">updateReviewForAdmin</strong></td>
<td valign="top"><a href="#reviewmodel">ReviewModel</a>!</td>
<td>

리뷰 수정 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#reviewupdateinputforadmin">ReviewUpdateInputForAdmin</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deletereviewforadmin">deleteReviewForAdmin</strong></td>
<td valign="top"><a href="#reviewmodel">ReviewModel</a>!</td>
<td>

리뷰 삭제 - 관리자용

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.writereview">writeReview</strong></td>
<td valign="top"><a href="#reviewmodel">ReviewModel</a>!</td>
<td>

리뷰 작성하기

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

리뷰 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#reviewwriteinput">ReviewWriteInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.sigungurefetch">sigunguRefetch</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

시군구 데이터 재셋팅

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signinnaver">signInNaver</strong></td>
<td valign="top"><a href="#authtokenresponse">AuthTokenResponse</a>!</td>
<td>

네이버 소셜 계정을 이용하여 로그인합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 네이버 계정입니다.
- `NOT_FOUND`: 가입하지 않은 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

네이버 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signupnaver">signUpNaver</strong></td>
<td valign="top"><a href="#signupresult">SignUpResult</a>!</td>
<td>

네이버 소셜 계정을 이용하여 회원가입합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 네이버 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

네이버 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#socialsignupinput">SocialSignUpInput</a>!</td>
<td>

회원가입 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.linknaver">linkNaver</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

이미 가입된 계정에 네이버 소셜 계정을 연결합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 네이버 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

네이버 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">userId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

사용자 ID

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">email</td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signinkakao">signInKakao</strong></td>
<td valign="top"><a href="#authtokenresponse">AuthTokenResponse</a>!</td>
<td>

카카오 소셜 계정을 이용하여 로그인합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 카카오 계정입니다.
- `NOT_FOUND`: 가입하지 않은 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카카오 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.signupkakao">signUpKakao</strong></td>
<td valign="top"><a href="#signupresult">SignUpResult</a>!</td>
<td>

카카오 소셜 계정을 이용하여 회원가입합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 카카오 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카카오 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#socialsignupinput">SocialSignUpInput</a>!</td>
<td>

회원가입 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.linkkakao">linkKakao</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

이미 가입된 계정에 카카오 소셜 계정을 연결합니다.

**에러 코드**
- `UNAUTHENTICATED`: 잘못된 카카오 계정입니다.

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">accessToken</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카카오 접근 토큰

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">userId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

사용자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.getkakaoaccesstoken">getKakaoAccessToken</strong></td>
<td valign="top"><a href="#kakaoaccessdata">KakaoAccessData</a>!</td>
<td>

카카오 access token 요청

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">code</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카카오 인가 코드

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">redirectUri</td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카카오 리다이렉트 URI

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createadvertisement">createAdvertisement</strong></td>
<td valign="top"><a href="#advertisementmodel">AdvertisementModel</a>!</td>
<td>

광고 생성 (관리자)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#advertisementcreateinput">AdvertisementCreateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.updateadvertisement">updateAdvertisement</strong></td>
<td valign="top"><a href="#advertisementmodel">AdvertisementModel</a>!</td>
<td>

광고 수정 (관리자)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

id

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">data</td>
<td valign="top"><a href="#advertisementupdateinput">AdvertisementUpdateInput</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mutation.deleteadvertisement">deleteAdvertisement</strong></td>
<td valign="top"><a href="#advertisementmodel">AdvertisementModel</a>!</td>
<td>

광고 삭제 (관리자)

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

id

</td>
</tr>
</tbody>
</table>

## Subscription
<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="subscription.receivecommunitypostreply">receiveCommunityPostReply</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

커뮤니티 게시물 댓글 수신

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">rootId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

상위 field 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscription.receivecommunitypost">receiveCommunityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

커뮤니티 게시물 수신

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">categoryId</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
</tbody>
</table>

## Objects

### Admin

관리자

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="admin.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.idx">idx</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.role">role</strong></td>
<td valign="top"><a href="#userrole">UserRole</a>!</td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.state">state</strong></td>
<td valign="top"><a href="#userstate">UserState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.realname">realname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

실명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.nickname">nickname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

닉네임

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.joinedat">joinedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.leavedat">leavedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

탈퇴 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.suspendedat">suspendedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

정지 처리된 시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.isfollowing">isFollowing</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내가 해당 사용자를 팔로잉한 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.avatar">avatar</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

프로필 이미지(아바타)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.socialtype">socialType</strong></td>
<td valign="top"><a href="#usersocialtype">UserSocialType</a></td>
<td>

가입 방법,null이면 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.profile">profile</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a></td>
<td>

유저 프로필

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.favoriteprofilecount">favoriteProfileCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 기업 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.favoriteannouncementcount">favoriteAnnouncementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 공고 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.favoriteportfoliocount">favoritePortfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 포트폴리오 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.portfoliocount">portfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포트폴리오 개수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.allow">allow</strong></td>
<td valign="top"><a href="#userallow">UserAllow</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.notificationsetting">notificationSetting</strong></td>
<td valign="top"><a href="#usernotificationsetting">UserNotificationSetting</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.announcementcount">announcementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 작성 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.announcementapplycount">announcementApplyCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 참여 횟수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

보유 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.pointchargeamount">pointChargeAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 충전 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자용 유저 메모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나 인지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="admin.socials">socials</strong></td>
<td valign="top">[<a href="#usersociallink">UserSocialLink</a>]!</td>
<td>

소셜 서비스 연결 리스트

</td>
</tr>
</tbody>
</table>

### AdminPostCategory

관리자가 올린 게시물의 카테고리

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategory.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategory.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategory.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategory.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategory.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카테고리 이름

</td>
</tr>
</tbody>
</table>

### AdminPostList

관리자가 올린 게시물 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostlist.edges">edges</strong></td>
<td valign="top">[<a href="#adminpostmodeledge">AdminPostModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### AdminPostModel

관리자가 올린 게시물

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostmodel.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostmodel.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostmodel.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
</tbody>
</table>

### AdminPostModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostmodeledge.node">node</strong></td>
<td valign="top"><a href="#adminpostmodel">AdminPostModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### AdministrativeActionDetail

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.date">date</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

처분일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.industry">industry</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

처분업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.type">type</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

처분유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.result">result</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

처분결과

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.violation">violation</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

위반내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="administrativeactiondetail.basis">basis</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

처분 근거

</td>
</tr>
</tbody>
</table>

### AdvertisementList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlist.edges">edges</strong></td>
<td valign="top">[<a href="#advertisementmodeledge">AdvertisementModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### AdvertisementModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.location">location</strong></td>
<td valign="top"><a href="#advertisementlocationenum">AdvertisementLocationEnum</a>!</td>
<td>

위치

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.state">state</strong></td>
<td valign="top"><a href="#advertisementstateenum">AdvertisementStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

url

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.image">image</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodel.mobileimage">mobileImage</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

모바일 이미지

</td>
</tr>
</tbody>
</table>

### AdvertisementModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementmodeledge.node">node</strong></td>
<td valign="top"><a href="#advertisementmodel">AdvertisementModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyList

입찰 참여 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplylist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplylist.edges">edges</strong></td>
<td valign="top">[<a href="#announcementapplymodeledge">AnnouncementApplyModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplylist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyModel

입찰 참여 신청서

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.estimatedamount">estimatedAmount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

최종 견적 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.state">state</strong></td>
<td valign="top"><a href="#announcementapplystateenum">AnnouncementApplyStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

신청자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.announcement">announcement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a></td>
<td>

관련 입찰 공고

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodel.estimatefiles">estimateFiles</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

견젹서 파일

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplymodeledge.node">node</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### AnnouncementDashboard

입찰 대시보드

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboard.designcount">designCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

설계, 인허가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboard.materialscount">materialsCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

자재(도소매, 대여, 생산, 제조)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboard.constructioncount">constructionCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

시공업체, 기술자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboard.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

업데이트 날짜

</td>
</tr>
</tbody>
</table>

### AnnouncementDashboardForAdminModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.todayuploadcount">todayUploadCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

업로드 현황 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.totaluploadcount">totalUploadCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

업로드 현황 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.todayapplicantscount">todayApplicantScount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

입찰 참여자 현황 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.totalapplicantscount">totalApplicantScount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

입찰 참여자 현황 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.todayannouncementresultcount">todayAnnouncementResultCount</strong></td>
<td valign="top"><a href="#announcementresultcount">AnnouncementResultCount</a>!</td>
<td>

입찰 결과 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementdashboardforadminmodel.totalannouncementresultcount">totalAnnouncementResultCount</strong></td>
<td valign="top"><a href="#announcementresultcount">AnnouncementResultCount</a>!</td>
<td>

입찰 결과 누계

</td>
</tr>
</tbody>
</table>

### AnnouncementList

공고 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementlist.edges">edges</strong></td>
<td valign="top">[<a href="#announcementmodeledge">AnnouncementModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### AnnouncementModel

입찰 공고

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isdeletedbyadmin">isDeletedByAdmin</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

관리자 삭제 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a>!</td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.uniqueid">uniqueId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a>!</td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a>!</td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a>!</td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.address">address</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a>!</td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.description">description</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.postingendat">postingEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

공고 게시 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.choosingendat">choosingEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

업체 선정 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a>!</td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

긴급 공사 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.state">state</strong></td>
<td valign="top"><a href="#announcementstateenum">AnnouncementStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isrecreated">isReCreated</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

재공고 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isapply">isApply</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

참여 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.applycnt">applyCnt</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

참여 신청 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.categories">categories</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]!</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.images">images</strong></td>
<td valign="top">[<a href="#file">File</a>!]!</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.mainimage">mainImage</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

대표 사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]!</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

관심 등록 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내 공고인지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.ishavevideo">isHaveVideo</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

동영상 파일 제공인지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.ishavedocs">isHaveDocs</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

도면,도서,기타 서류 제공하는지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.myapply">myApply</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a></td>
<td>

나의 입찰 신청서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.licenses">licenses</strong></td>
<td valign="top">[<a href="#licensemodel">LicenseModel</a>!]</td>
<td>

면허

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodel.appliesforadmin">appliesForAdmin</strong></td>
<td valign="top">[<a href="#announcementapplymodel">AnnouncementApplyModel</a>!]!</td>
<td>

신청 리스트 - 관리자

</td>
</tr>
</tbody>
</table>

### AnnouncementModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementmodeledge.node">node</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### AnnouncementResultCount

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementresultcount.selected">selected</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

낙찰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementresultcount.unselected">unselected</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

유찰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementresultcount.recreated">reCreated</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

재등록

</td>
</tr>
</tbody>
</table>

### AnnouncementTempList

임시 공고 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtemplist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtemplist.edges">edges</strong></td>
<td valign="top">[<a href="#announcementtempmodeledge">AnnouncementTempModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtemplist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### AnnouncementTempModel

입찰 공고 임시저장

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.step">step</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

스텝

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.postingendat">postingEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

공고 게시 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

긴급 공사 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.categories">categories</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]!</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.images">images</strong></td>
<td valign="top">[<a href="#file">File</a>!]!</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]!</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.mainimage">mainImage</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

메인 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodel.licenses">licenses</strong></td>
<td valign="top">[<a href="#licensemodel">LicenseModel</a>!]</td>
<td>

면허

</td>
</tr>
</tbody>
</table>

### AnnouncementTempModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempmodeledge.node">node</strong></td>
<td valign="top"><a href="#announcementtempmodel">AnnouncementTempModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### AuthTokenResponse

토큰 요청의 대한 응답

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="authtokenresponse.tokentype">tokenType</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

토큰 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="authtokenresponse.accesstoken">accessToken</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

접근 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="authtokenresponse.expiresin">expiresIn</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

접근 토큰 만료 시간(초)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="authtokenresponse.refreshtoken">refreshToken</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

갱신 토큰

</td>
</tr>
</tbody>
</table>

### BalanceDetail

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="balancedetail.year">year</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

회계연도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="balancedetail.assets">assets</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

총자산

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="balancedetail.liabilities">liabilities</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

총부채

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="balancedetail.capitalstock">capitalStock</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

자본금

</td>
</tr>
</tbody>
</table>

### BankCodeList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bankcodelist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodelist.edges">edges</strong></td>
<td valign="top">[<a href="#bankcodemodeledge">BankCodeModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodelist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### BankCodeModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### BankCodeModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodemodeledge.node">node</strong></td>
<td valign="top"><a href="#bankcodemodel">BankCodeModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### Banner

배너

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="banner.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="banner.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크 URL

</td>
</tr>
</tbody>
</table>

### CRIList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="crilist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crilist.edges">edges</strong></td>
<td valign="top">[<a href="#crimodeledge">CRIModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crilist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CRIModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodel.priority">priority</strong></td>
<td valign="top"><a href="#cripriorityenum">CRIPriorityEnum</a>!</td>
<td>

cri 우선순위

</td>
</tr>
</tbody>
</table>

### CRIModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="crimodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crimodeledge.node">node</strong></td>
<td valign="top"><a href="#crimodel">CRIModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CategoryList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorylist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorylist.edges">edges</strong></td>
<td valign="top">[<a href="#categorymodeledge">CategoryModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorylist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CategoryModel

업종 항목 카테고리

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.type">type</strong></td>
<td valign="top"><a href="#categorytypeenum">CategoryTypeEnum</a>!</td>
<td>

분류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.code">code</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

분류 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.kisccodes">kiscCodes</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

한국표준산업분류 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodel.parent">parent</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a></td>
<td>

상위 카테고리

</td>
</tr>
</tbody>
</table>

### CategoryModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorymodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorymodeledge.node">node</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CommunityCategory

커뮤니티 카테고리

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커뮤니티 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

커뮤니티 카테고리 배치 순서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategory.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 카테고리 즐켜찾기 여부

</td>
</tr>
</tbody>
</table>

### CommunityCategoryEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryedge.node">node</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CommunityCategoryList

커뮤니티 카테고리 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategorylist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategorylist.edges">edges</strong></td>
<td valign="top">[<a href="#communitycategoryedge">CommunityCategoryEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategorylist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CommunityPost

커뮤니티 게시물

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.addressname">addressName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.viewcount">viewCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

조회수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.likecount">likeCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

좋아요 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.replycount">replyCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

댓글 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.islike">isLike</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나의 좋아요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.category">category</strong></td>
<td valign="top"><a href="#communitycategory">CommunityCategory</a></td>
<td>

연결 커뮤니티 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

보이기 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

이미지, 영상 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.hashtags">hashtags</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

해시태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.usertags">usertags</strong></td>
<td valign="top">[<a href="#user">User</a>!]</td>
<td>

사용자 태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.deeplinkurl">deepLinkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.ispinned">isPinned</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.pinnedat">pinnedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.ishide">isHide</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나의 숨기기 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypost.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 카테고리 즐겨찾기 추가 여부

</td>
</tr>
</tbody>
</table>

### CommunityPostEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostedge.node">node</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CommunityPostList

커뮤니티 게시물 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostlist.edges">edges</strong></td>
<td valign="top">[<a href="#communitypostedge">CommunityPostEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CommunityPostReply

커뮤니티 게시물 댓글

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

댓글 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.likecount">likeCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

좋아요 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.usertags">usertags</strong></td>
<td valign="top">[<a href="#user">User</a>!]</td>
<td>

사용자 태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.replies">replies</strong></td>
<td valign="top">[<a href="#communitypostreply">CommunityPostReply</a>!]</td>
<td>

대댓글 조회

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.islike">isLike</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

(대)댓글 좋아요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.parent">parent</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a></td>
<td>

대댓글단 댓글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreply.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내 댓글인지 여부

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyedge.node">node</strong></td>
<td valign="top"><a href="#communitypostreply">CommunityPostReply</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyList

커뮤니티 게시물 댓글 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplylist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplylist.edges">edges</strong></td>
<td valign="top">[<a href="#communitypostreplyedge">CommunityPostReplyEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplylist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CommunityReport

커뮤니티 신고 모델

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.targetid">targetId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 커뮤니티 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.category">category</strong></td>
<td valign="top"><a href="#communityreportcategoryenumtype">CommunityReportCategoryEnumType</a></td>
<td>

신고 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.etc">etc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

기타 예비용 필드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.type">type</strong></td>
<td valign="top"><a href="#communityreporttype">CommunityReportType</a></td>
<td>

신고 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.state">state</strong></td>
<td valign="top"><a href="#communityreportstateenumtype">CommunityReportStateEnumType</a></td>
<td>

신고 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.targetinfo">targetInfo</strong></td>
<td valign="top"><a href="#communityreporttarget">CommunityReportTarget</a></td>
<td>

신고 타겟 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

관리자 메모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreport.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

신고 파일

</td>
</tr>
</tbody>
</table>

### CommunityReportEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportedge.node">node</strong></td>
<td valign="top"><a href="#communityreport">CommunityReport</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### CommunityReportList

커뮤니티 신고 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportlist.edges">edges</strong></td>
<td valign="top">[<a href="#communityreportedge">CommunityReportEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CompanyInfoList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="companyinfolist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfolist.edges">edges</strong></td>
<td valign="top">[<a href="#companyinfomodeledge">CompanyInfoModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfolist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### CompanyInfoModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

회사명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.businessregistrationnumber">businessRegistrationNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자등록번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

프로필 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.publicamount">publicAmount</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

공공 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.privateamount">privateAmount</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

민간 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.totalamount">totalAmount</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

합계 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.source">source</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

출처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.patent">patent</strong></td>
<td valign="top">[<a href="#patentdetail">PatentDetail</a>!]!</td>
<td>

특허

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.affiliate">affiliate</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

관계회사

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.cri">cri</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

신용 등급

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.balance">balance</strong></td>
<td valign="top">[<a href="#balancedetail">BalanceDetail</a>!]!</td>
<td>

재무 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.income">income</strong></td>
<td valign="top">[<a href="#incomedetail">IncomeDetail</a>!]!</td>
<td>

손익 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.administrativeaction">administrativeAction</strong></td>
<td valign="top">[<a href="#administrativeactiondetail">AdministrativeActionDetail</a>!]!</td>
<td>

행정 처분 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.companytype">companyType</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자 업태업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.licenses">licenses</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

면허

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.mainbusiness">mainBusiness</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주력 사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.address">address</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주소(본점)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

상세주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.zipcode">zipCode</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

우편번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.phone">phone</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

전화번호(본점)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.fax">fax</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

팩스

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.establishmentdate">establishmentDate</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

설립일자(경력)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.staffcount">staffCount</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.settlementdate">settlementDate</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

결산일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.majorstockholder">majorStockholder</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주요 주주

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.majorstockholderstake">majorStockHolderStake</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주요 주주 지분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.description">description</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임 대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.snslink">snsLink</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

sns 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.representativename">representativeName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.representativephone">representativePhone</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

대표자 전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.representativeemail">representativeEmail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

대표자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.managerphone">managerPhone</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

담당자 전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.manageremail">managerEmail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

담당자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodel.category">category</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력 업종

</td>
</tr>
</tbody>
</table>

### CompanyInfoModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfomodeledge.node">node</strong></td>
<td valign="top"><a href="#companyinfomodel">CompanyInfoModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### EnterpriseDashboardModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="enterprisedashboardmodel.todaycount">todayCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

당일 추가 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisedashboardmodel.totalcount">totalCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

총 업체 수

</td>
</tr>
</tbody>
</table>

### EnterpriseList

업체 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="enterpriselist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterpriselist.edges">edges</strong></td>
<td valign="top">[<a href="#userprofileedge">UserProfileEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterpriselist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### Event

이벤트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="event.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="event.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크 URL

</td>
</tr>
</tbody>
</table>

### Faq

자주 묻는 질문

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="faq.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faq.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faq.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faq.question">question</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

질문

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faq.answer">answer</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

답변

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faq.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

우선순위

</td>
</tr>
</tbody>
</table>

### File

파일

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="file.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.filename">filename</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

원본 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.mimetype">mimetype</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

MIME 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.md5">md5</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

MD5 체크섬

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.size">size</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

파일 크기 (바이트)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

우선 순위 (정렬용)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.url">url</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

원본 URL

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.thumbnailurl">thumbnailURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

썸네일용 URL (240px)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.lowqualityurl">lowQualityURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

저화질 URL (480px)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="file.highqualityurl">highQualityURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고화질 URL (1080px)

</td>
</tr>
</tbody>
</table>

### FinancialGraphRow

그래프 데이터

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="financialgraphrow.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

index

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialgraphrow.date">date</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

날짜

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialgraphrow.amount">amount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

수

</td>
</tr>
</tbody>
</table>

### FinancialModel

재무/신용평가/소송 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.salesinfo">salesInfo</strong></td>
<td valign="top"><a href="#financialsalesinfo">FinancialSalesInfo</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.financialinfo">financialInfo</strong></td>
<td valign="top"><a href="#financialtable">FinancialTable</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.faultinfo">faultInfo</strong></td>
<td valign="top"><a href="#financialtable">FinancialTable</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.publicamount">publicAmount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

공공금액(억원)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.privateamount">privateAmount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

민간금액(억원)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialmodel.cri">cri</strong></td>
<td valign="top"><a href="#crimodel">CRIModel</a></td>
<td>

cri

</td>
</tr>
</tbody>
</table>

### FinancialSalesInfo

매출액/영업이익 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.salesyear">salesYear</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매출액 년도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.salesamount">salesAmount</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매출액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.salesyoy">salesYoY</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매출액 전년대비

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.salesavg">salesAvg</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매출액 3년 평균

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.salesamounts">salesAmounts</strong></td>
<td valign="top">[<a href="#financialgraphrow">FinancialGraphRow</a>!]</td>
<td>

매출액 그래프 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.businessyear">businessYear</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

영업이익 년도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.businessamount">businessAmount</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

영업이익

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.businessyoy">businessYoY</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

영업이익 전년대비

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.businessavg">businessAvg</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

영업이익 3년 평균

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialsalesinfo.businessamounts">businessAmounts</strong></td>
<td valign="top">[<a href="#financialgraphrow">FinancialGraphRow</a>!]</td>
<td>

영업이익 그래프 데이터

</td>
</tr>
</tbody>
</table>

### FinancialTable

재무/행정처분 이력 테이블

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="financialtable.columns">columns</strong></td>
<td valign="top">[<a href="#string">String</a>!]!</td>
<td>

컬럼 데이터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialtable.rows">rows</strong></td>
<td valign="top">[<a href="#financialtablerow">FinancialTableRow</a>!]!</td>
<td>

row 데이터

</td>
</tr>
</tbody>
</table>

### FinancialTableRow

재무/행정처분 이력 테이블 row

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="financialtablerow.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="financialtablerow.list">list</strong></td>
<td valign="top">[<a href="#string">String</a>]!</td>
<td></td>
</tr>
</tbody>
</table>

### FinedAccount

아이디 찾기를 통해 찾은 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="finedaccount.loginid">loginId</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

로그인 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="finedaccount.socialtypes">socialTypes</strong></td>
<td valign="top">[<a href="#usersocialtype">UserSocialType</a>!]</td>
<td>

연동된 소셜 계정 리스트, 없을시 undefined

</td>
</tr>
</tbody>
</table>

### IncomeDetail

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="incomedetail.year">year</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

회계연도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="incomedetail.sales">sales</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매출액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="incomedetail.operatingprofit">operatingProfit</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

영업이익

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="incomedetail.netincome">netIncome</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

당기순이익

</td>
</tr>
</tbody>
</table>

### Inquire

문의하기 데이터

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquire.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.type">type</strong></td>
<td valign="top"><a href="#inquiretype">InquireType</a>!</td>
<td>

문의 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.state">state</strong></td>
<td valign="top"><a href="#inquirestate">InquireState</a>!</td>
<td>

문의 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.answercontent">answerContent</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

답변

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.answereddat">answereddAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

답변일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

문의 파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquire.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자용 유저 메모

</td>
</tr>
</tbody>
</table>

### InquireEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquireedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquireedge.node">node</strong></td>
<td valign="top"><a href="#inquire">Inquire</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### InquireList

문의하기 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquirelist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirelist.edges">edges</strong></td>
<td valign="top">[<a href="#inquireedge">InquireEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirelist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### KakaoAccessData

카카오 Access Token

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="kakaoaccessdata.jwtdata">jwtData</strong></td>
<td valign="top"><a href="#kakaojwtdata">KakaoJWTData</a>!</td>
<td>

발급 JWT 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaoaccessdata.isjoin">isJoin</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

가입된 계정인지?

</td>
</tr>
</tbody>
</table>

### KakaoJWTData

카카오 JWT Data

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.access_token">access_token</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.token_type">token_type</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.refresh_token">refresh_token</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.expires_in">expires_in</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.scope">scope</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="kakaojwtdata.refresh_token_expires_in">refresh_token_expires_in</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### LicenseList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="licenselist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licenselist.edges">edges</strong></td>
<td valign="top">[<a href="#licensemodeledge">LicenseModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licenselist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### LicenseModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="licensemodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensemodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensemodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensemodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensemodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### LicenseModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="licensemodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensemodeledge.node">node</strong></td>
<td valign="top"><a href="#licensemodel">LicenseModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### MatchPost

매칭 게시물

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.category">category</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a></td>
<td>

매칭 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.detail">detail</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

상세정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.addressname">addressName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.addresssido">addressSiDo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 시,도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.addresssigungu">addressSiGunGu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.viewcount">viewCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

조회수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.likecount">likeCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

좋아요 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.replycount">replyCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

댓글 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.islike">isLike</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나의 좋아요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.state">state</strong></td>
<td valign="top"><a href="#matchpoststateenum">MatchPostStateEnum</a>!</td>
<td>

매칭 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.trader">trader</strong></td>
<td valign="top"><a href="#member">Member</a></td>
<td>

거래 대상자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

보이기 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.type">type</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a></td>
<td>

게시물 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.usertags">usertags</strong></td>
<td valign="top">[<a href="#user">User</a>!]</td>
<td>

사용자 태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.deeplinkurl">deepLinkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpost.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

게시물 이미지, 영상

</td>
</tr>
</tbody>
</table>

### MatchPostCategory

매칭 카테고리

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

매칭 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

매칭 카테고리 배치 순서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategory.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

매칭 카테고리 즐켜찾기 여부

</td>
</tr>
</tbody>
</table>

### MatchPostCategoryEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryedge.node">node</strong></td>
<td valign="top"><a href="#matchpostcategory">MatchPostCategory</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### MatchPostCategoryList

매칭 카테고리 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategorylist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategorylist.edges">edges</strong></td>
<td valign="top">[<a href="#matchpostcategoryedge">MatchPostCategoryEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategorylist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### MatchPostEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostedge.node">node</strong></td>
<td valign="top"><a href="#matchpost">MatchPost</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### MatchPostList

매칭 게시물 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostlist.edges">edges</strong></td>
<td valign="top">[<a href="#matchpostedge">MatchPostEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### MatchPostType

매칭 게시물 타입

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttype.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttype.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttype.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttype.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttype.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

매칭 게시물 타입 이름

</td>
</tr>
</tbody>
</table>

### MatchPostTypeEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeedge.node">node</strong></td>
<td valign="top"><a href="#matchposttype">MatchPostType</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### MatchPostTypeList

매칭 게시물 타입 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypelist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypelist.edges">edges</strong></td>
<td valign="top">[<a href="#matchposttypeedge">MatchPostTypeEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypelist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### Member

일반 사용자

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="member.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.idx">idx</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.role">role</strong></td>
<td valign="top"><a href="#userrole">UserRole</a>!</td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.state">state</strong></td>
<td valign="top"><a href="#userstate">UserState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.realname">realname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

실명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.nickname">nickname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

닉네임

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.joinedat">joinedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.leavedat">leavedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

탈퇴 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.suspendedat">suspendedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

정지 처리된 시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.isfollowing">isFollowing</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내가 해당 사용자를 팔로잉한 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.avatar">avatar</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

프로필 이미지(아바타)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.socialtype">socialType</strong></td>
<td valign="top"><a href="#usersocialtype">UserSocialType</a></td>
<td>

가입 방법,null이면 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.profile">profile</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a></td>
<td>

유저 프로필

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.favoriteprofilecount">favoriteProfileCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 기업 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.favoriteannouncementcount">favoriteAnnouncementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 공고 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.favoriteportfoliocount">favoritePortfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 포트폴리오 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.portfoliocount">portfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포트폴리오 개수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.allow">allow</strong></td>
<td valign="top"><a href="#userallow">UserAllow</a></td>
<td>

동의 항목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.notificationsetting">notificationSetting</strong></td>
<td valign="top"><a href="#usernotificationsetting">UserNotificationSetting</a></td>
<td>

알림 설정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.announcementcount">announcementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 작성 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.announcementapplycount">announcementApplyCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 참여 횟수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

보유 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.pointchargeamount">pointChargeAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 충전 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자용 유저 메모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나 인지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.socials">socials</strong></td>
<td valign="top">[<a href="#usersociallink">UserSocialLink</a>]!</td>
<td>

소셜 서비스 연결 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="member.subscriptionauth">subscriptionAuth</strong></td>
<td valign="top"><a href="#paymentitemauthenum">PaymentItemAuthEnum</a></td>
<td>

열람/발급 권한, 구독한게 없으면 null

</td>
</tr>
</tbody>
</table>

### MemberCount

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="membercount.corporation">corporation</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

법인

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="membercount.private">private</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

개인 사업자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="membercount.engineer">engineer</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

기술자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="membercount.common">common</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

일반

</td>
</tr>
</tbody>
</table>

### MyAnnouncementDashboard

나의 공고 대시보드

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="myannouncementdashboard.mypostedannouncementcount">myPostedAnnouncementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

입찰 게시중

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myannouncementdashboard.appliedbidcount">appliedBidCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

입찰 참여중

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myannouncementdashboard.mytempannouncementcount">myTempAnnouncementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

작성 중인 공고

</td>
</tr>
</tbody>
</table>

### MyAvailableAnnouncementDashboard

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="myavailableannouncementdashboard.announcementtotalcount">announcementTotalCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

신청 가능한 공고 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myavailableannouncementdashboard.totalamount">totalAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

최대 낙찰금

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myavailableannouncementdashboard.items">items</strong></td>
<td valign="top">[<a href="#myavailableannouncementdashboarditem">MyAvailableAnnouncementDashboardItem</a>!]!</td>
<td></td>
</tr>
</tbody>
</table>

### MyAvailableAnnouncementDashboardItem

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="myavailableannouncementdashboarditem.category">category</strong></td>
<td valign="top"><a href="#categorymodel">CategoryModel</a>!</td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myavailableannouncementdashboarditem.announcementcount">announcementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 수

</td>
</tr>
</tbody>
</table>

### MyPointRefundInfo

내 포인트 환전 대시보드

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="mypointrefundinfo.refundprocessingpoint">refundProcessingPoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 진행 중인 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="mypointrefundinfo.refundedtotalpoint">refundedTotalPoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

총 환급받은 포인트

</td>
</tr>
</tbody>
</table>

### MyReviewDashboard

내가 받은 리뷰 현황

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.avgscore">avgScore</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 평균

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.totalreviewcnt">totalReviewCnt</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

총 받은 리뷰수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.start5rate">start5Rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 5점 비율

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.start4rate">start4Rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 4점 비율

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.start3rate">start3Rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 3점 비율

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.start2rate">start2Rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 2점 비율

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="myreviewdashboard.start1rate">start1Rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

별점 1점 비율

</td>
</tr>
</tbody>
</table>

### Notice

공지사항

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notice.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notice.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notice.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notice.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notice.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
</tbody>
</table>

### Notification

알림

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notification.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.message">message</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.type">type</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.relationid">relationId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

연관 데이터의 ID (타입을 참고하여 사용)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크 URL 주소 (타입을 참고하여 사용)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.imageurl">imageURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.iscreatedforadmin">isCreatedForAdmin</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

관리자 임의 전송 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.isread">isRead</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

해당 알림 읽음 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notification.communitypost">communityPost</strong></td>
<td valign="top"><a href="#communitypost">CommunityPost</a></td>
<td></td>
</tr>
</tbody>
</table>

### NotificationEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationedge.node">node</strong></td>
<td valign="top"><a href="#notification">Notification</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### NotificationList

알림 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationlist.edges">edges</strong></td>
<td valign="top">[<a href="#notificationedge">NotificationEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### NotificationStorageList

알림 저장소 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragelist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragelist.edges">edges</strong></td>
<td valign="top">[<a href="#notificationstoragemodeledge">NotificationStorageModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragelist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### NotificationStorageModel

알림 저장소

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.message">message</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.type">type</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a></td>
<td>

알림 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.relationid">relationId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.imageurl">imageURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이미지  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.target">target</strong></td>
<td valign="top"><a href="#notificationstoragetargettype">NotificationStorageTargetType</a></td>
<td>

수신 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.scheduledat">scheduledAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

예약 발송 시간, null이면 즉시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodel.issend">isSend</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

전송 여부

</td>
</tr>
</tbody>
</table>

### NotificationStorageModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragemodeledge.node">node</strong></td>
<td valign="top"><a href="#notificationstoragemodel">NotificationStorageModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### OpenSourceModel

OpenSource모델

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

소스명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.publisher">publisher</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.licensefileurl">licenseFileUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

라이센스 URL

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.licenses">licenses</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

라이센스 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="opensourcemodel.repository">repository</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

저장소

</td>
</tr>
</tbody>
</table>

### PageInfo

페이지 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pageinfo.haspreviouspage">hasPreviousPage</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

이전 페이지 존재 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pageinfo.hasnextpage">hasNextPage</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

다음 페이지 존재 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pageinfo.startcursor">startCursor</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현재 페이지의 처음 데이터 커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pageinfo.endcursor">endCursor</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현재 페이지의 마지막 데이터 커서

</td>
</tr>
</tbody>
</table>

### PageViewsModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pageviewsmodel.date">date</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pageviewsmodel.views">views</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

방문자 수

</td>
</tr>
</tbody>
</table>

### PatentDetail

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="patentdetail.type">type</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

특허 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="patentdetail.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

특허명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="patentdetail.applicationnumber">applicationNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

출원 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="patentdetail.applicantcode">applicantCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

출원인 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="patentdetail.applicationdate">applicationDate</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

등록일

</td>
</tr>
</tbody>
</table>

### PaymentItemModel

결제 항목

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.type">type</strong></td>
<td valign="top"><a href="#paymentitemtypeenum">PaymentItemTypeEnum</a>!</td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.auth">auth</strong></td>
<td valign="top"><a href="#paymentitemauthenum">PaymentItemAuthEnum</a></td>
<td>

구독 권한 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.priority">priority</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

순번

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.freepoint">freePoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

무상 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.price">price</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

결제금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemmodel.isuse">isUse</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

활용 여부

</td>
</tr>
</tbody>
</table>

### PaymentList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentlist.edges">edges</strong></td>
<td valign="top">[<a href="#paymentmodeledge">PaymentModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PaymentMethod

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.cardname">cardName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카드사 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.cardnumber">cardNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카드번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethod.idnumber">idNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

개인: 생년월일(YYMMDD), 법인: 사업자번호(10자리)

</td>
</tr>
</tbody>
</table>

### PaymentModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.amount">amount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.moid">moid</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주문 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.state">state</strong></td>
<td valign="top"><a href="#paymentstateenumtype">PaymentStateEnumType</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.paymethod">payMethod</strong></td>
<td valign="top"><a href="#paymentmethodenumtype">PaymentMethodEnumType</a></td>
<td>

결제수단

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.paidat">paidAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

결제 일시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.buyer">buyer</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

구매자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.item">item</strong></td>
<td valign="top"><a href="#paymentitemmodel">PaymentItemModel</a>!</td>
<td>

상품

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.lastrefund">lastRefund</strong></td>
<td valign="top"><a href="#paymentrefundmodel">PaymentRefundModel</a></td>
<td>

마지막 환불

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodel.subscription">subscription</strong></td>
<td valign="top"><a href="#subscriptionapplymodel">SubscriptionApplyModel</a></td>
<td>

구독

</td>
</tr>
</tbody>
</table>

### PaymentModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmodeledge.node">node</strong></td>
<td valign="top"><a href="#paymentmodel">PaymentModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### PaymentRefundList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundlist.edges">edges</strong></td>
<td valign="top">[<a href="#paymentrefundmodeledge">PaymentRefundModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PaymentRefundModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.state">state</strong></td>
<td valign="top"><a href="#paymentrefundstateenum">PaymentRefundStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.requestingdate">requestingDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

요청일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodel.processingdate">processingDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

처리일

</td>
</tr>
</tbody>
</table>

### PaymentRefundModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundmodeledge.node">node</strong></td>
<td valign="top"><a href="#paymentrefundmodel">PaymentRefundModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### PaymentResponseModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.goodsname">GoodsName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

결제상품명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.amt">Amt</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.mid">MID</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

상점아이디

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.edidate">EdiDate</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

요청 시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.moid">Moid</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

상품주문번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentresponsemodel.signdata">SignData</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

위변조 검증 데이터

</td>
</tr>
</tbody>
</table>

### Point

포인트 내역

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="point.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.type">type</strong></td>
<td valign="top"><a href="#pointtypeenum">PointTypeEnum</a>!</td>
<td>

발생 주체

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.reason">reason</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

발생 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.targetid">targetId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

target id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="point.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트

</td>
</tr>
</tbody>
</table>

### PointDashboard

포인트 현황

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointdashboard.nowpoint">nowPoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

현재 남은 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointdashboard.totalpoint">totalPoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

총 받은 포인트

</td>
</tr>
</tbody>
</table>

### PointEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointedge.node">node</strong></td>
<td valign="top"><a href="#point">Point</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### PointList

포인트 내역 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointlist.edges">edges</strong></td>
<td valign="top">[<a href="#pointedge">PointEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PointRefund

포인트 환전 요청 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.state">state</strong></td>
<td valign="top"><a href="#pointrefundstateenum">PointRefundStateEnum</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.processingdate">processingDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

처리날짜

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.point">point</strong></td>
<td valign="top"><a href="#point">Point</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.failreason">failReason</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

거절 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.reason">reason</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환전 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.bankname">bankName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

은행명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.bankowner">bankOwner</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

은행계좌 소유주

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.bankaccount">bankAccount</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

은행계좌

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.amount">amount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 받을 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefund.user">user</strong></td>
<td valign="top"><a href="#member">Member</a></td>
<td>

신청자

</td>
</tr>
</tbody>
</table>

### PointRefundEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundedge.node">node</strong></td>
<td valign="top"><a href="#pointrefund">PointRefund</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### PointRefundList

포인트 환전 요청 정보 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundlist.edges">edges</strong></td>
<td valign="top">[<a href="#pointrefundedge">PointRefundEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PointSubscriptionDashboardForAdmin

포인트 및 구독

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaypointpurchasedmembercount">todayPointPurchasedMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 구매 인원수 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalpointpurchasedmembercount">totalPointPurchasedMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 구매 인원수 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaypointpurchasedamount">todayPointPurchasedAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 구매 금액 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalpointpurchasedamount">totalPointPurchasedAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 구매 금액 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaypointrefundcount">todayPointRefundCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 인원수 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalpointrefundcount">totalPointRefundCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 인원수 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaypointrefundamount">todayPointRefundAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 금액 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalpointrefundamount">totalPointRefundAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 금액 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaysubscriptionmembercount">todaySubscriptionMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

구독 인원수 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalsubscriptionmembercount">totalSubscriptionMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

구독 인원수 누계

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.todaysubscriptionamount">todaySubscriptionAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

구독 금액 현재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsubscriptiondashboardforadmin.totalsubscriptionamount">totalSubscriptionAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

구독 금액 누계

</td>
</tr>
</tbody>
</table>

### Popup

팝업

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="popup.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popup.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크 URL

</td>
</tr>
</tbody>
</table>

### PortfolioList

포트폴리오 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliolist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliolist.edges">edges</strong></td>
<td valign="top">[<a href="#portfoliomodeledge">PortfolioModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliolist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PortfolioModel

포트폴리오

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.locationsi">locationSi</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.locationdo">locationDo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.constructiontype">constructionType</strong></td>
<td valign="top"><a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a>!</td>
<td>

공사 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.projectsize">projectSize</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

프로젝트 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a>!</td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액이 직접기재시 서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.servicetermstart">serviceTermStart</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

서비스 기간 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.servicetermend">serviceTermEnd</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

서비스 기간 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.description">description</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제공 서비스 상세 설명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

포트폴리오가 나타나는지 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.isrecommended">isRecommended</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

추천 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.images">images</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

등록된 사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.mainimage">mainImage</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

대표 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.categories">categories</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

등록된 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

관심 등록 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodel.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내가 작성한 포트폴리오인지 여부

</td>
</tr>
</tbody>
</table>

### PortfolioModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliomodeledge.node">node</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationList

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationlist.edges">edges</strong></td>
<td valign="top">[<a href="#portfoliorecommendationmodeledge">PortfolioRecommendationModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationModel

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.state">state</strong></td>
<td valign="top"><a href="#portfoliorecommendationstateenum">PortfolioRecommendationStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodel.portfolio">portfolio</strong></td>
<td valign="top"><a href="#portfoliomodel">PortfolioModel</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PortfolioRecommendationModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationmodeledge.node">node</strong></td>
<td valign="top"><a href="#portfoliorecommendationmodel">PortfolioRecommendationModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### ProfileCompanyInfo

프로필 법인 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.companycode">companyCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.companytype">companyType</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업태업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.mainbusiness">mainBusiness</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력 사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.phones">phones</strong></td>
<td valign="top">[<a href="#profileinfophone">ProfileInfoPhone</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.addresses">addresses</strong></td>
<td valign="top">[<a href="#profileinfoaddress">ProfileInfoAddress</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.settleaccountday">settleAccountDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

결산일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.stockholders">stockholders</strong></td>
<td valign="top">[<a href="#profileinfostockholders">ProfileInfoStockholders</a>!]</td>
<td>

주요 주주들

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.managerphonenumber">managerPhoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.manageremail">managerEmail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.maincategory">mainCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.mainsubcategory">mainSubCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.logoimg">logoImg</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

로고 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.mainbusinessmenuimg">mainBusinessMenuImg</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

주력업종 단가표

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfo.licenses">licenses</strong></td>
<td valign="top">[<a href="#licensemodel">LicenseModel</a>!]!</td>
<td>

면허

</td>
</tr>
</tbody>
</table>

### ProfileConsumerInfo

프로필 일반 소비자 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.maincategory">mainCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.mainsubcategory">mainSubCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfo.logoimg">logoImg</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

로고 이미지

</td>
</tr>
</tbody>
</table>

### ProfileDashboard

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profiledashboard.designcount">designCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

설계, 인허가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profiledashboard.materialscount">materialsCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

자재(도소매, 대여, 생산, 제조)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profiledashboard.constructioncount">constructionCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

시공업체, 기술자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profiledashboard.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

업데이트 날짜

</td>
</tr>
</tbody>
</table>

### ProfileEngineerInfo

프로필 기술자 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.phones">phones</strong></td>
<td valign="top">[<a href="#profileinfophone">ProfileInfoPhone</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.addresses">addresses</strong></td>
<td valign="top">[<a href="#profileinfoaddress">ProfileInfoAddress</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.maincategory">mainCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.mainsubcategory">mainSubCategory</strong></td>
<td valign="top">[<a href="#categorymodel">CategoryModel</a>!]</td>
<td>

주력업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.logoimg">logoImg</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

로고 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfo.mainbusinessmenuimg">mainBusinessMenuImg</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

주력업종 단가표

</td>
</tr>
</tbody>
</table>

### ProfileInfoAddress

프로필 주소 모델

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.postcode">postCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddress.isfirst">isFirst</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

첫번째인지(본점)

</td>
</tr>
</tbody>
</table>

### ProfileInfoPhone

프로필 휴대폰 모델

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophone.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophone.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophone.isfirst">isFirst</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

첫번째인지(본점)

</td>
</tr>
</tbody>
</table>

### ProfileInfoStockholders

프로필 주요 주주들 모델

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholders.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholders.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholders.rate">rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Report

신고 내역

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="report.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.category">category</strong></td>
<td valign="top"><a href="#reportcategoryenumtype">ReportCategoryEnumType</a>!</td>
<td>

신고 대상의 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

신고 내용 (500자 이하)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.etc">etc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비고

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.state">state</strong></td>
<td valign="top"><a href="#reportstateenumtype">ReportStateEnumType</a>!</td>
<td>

신고 처리 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.author">author</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

신고 작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.targetuser">targetUser</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

신고 당한 사용자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.files">files</strong></td>
<td valign="top">[<a href="#file">File</a>!]</td>
<td>

신고 파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="report.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자용 유저 메모

</td>
</tr>
</tbody>
</table>

### ReportEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportedge.node">node</strong></td>
<td valign="top"><a href="#report">Report</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### ReportList

신고 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportlist.edges">edges</strong></td>
<td valign="top">[<a href="#reportedge">ReportEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### ReviewList

리뷰 리스트

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewlist.edges">edges</strong></td>
<td valign="top">[<a href="#reviewmodeledge">ReviewModelEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### ReviewModel

리뷰

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.state">state</strong></td>
<td valign="top"><a href="#reviewstateenum">ReviewStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.score">score</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.context">context</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

리뷰 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

리뷰가 보이는지 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.writtenat">writtenAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작성일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.announcement">announcement</strong></td>
<td valign="top"><a href="#announcementmodel">AnnouncementModel</a></td>
<td>

관련 입찰 공고

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.announcementapply">announcementApply</strong></td>
<td valign="top"><a href="#announcementapplymodel">AnnouncementApplyModel</a></td>
<td>

관련 입찰 공고 참여

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodel.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내가 작성한 리뷰인지 여부

</td>
</tr>
</tbody>
</table>

### ReviewModelEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodeledge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewmodeledge.node">node</strong></td>
<td valign="top"><a href="#reviewmodel">ReviewModel</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### ServiceManage

서비스 운영 정보

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.representativename">representativeName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.mailordersalesregistrationnumber">mailOrderSalesRegistrationNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

통신판매업신고번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.businesslicense">businessLicense</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자등록번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.companyaddress">companyAddress</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.serviceterms">serviceTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

서비스이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.refundterms">refundTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환불규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.exchangeterms">exchangeTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환급 규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.kakaochannel">kakaoChannel</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

카카오 채널

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.marketingterms">marketingTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

마켓팅규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.personalprocessingpolicy">personalProcessingPolicy</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

개인정보처리방침

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.withdrawalterms">withdrawalTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

탈퇴약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.thirdpartyconsent">thirdPartyConsent</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제 3자 정보제공 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.paidserviceterms">paidServiceTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

유료서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.locationinfoterm">locationInfoTerm</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

위치기반 서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.kakaotalknotificationconsent">kakaotalkNotificationConsent</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

카카오톡 광고 알림 수신 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanage.opensource">openSource</strong></td>
<td valign="top">[<a href="#opensourcemodel">OpenSourceModel</a>!]</td>
<td>

오픈소스 리스트

</td>
</tr>
</tbody>
</table>

### SignUpResult

회원가입 결과

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="signupresult.user">user</strong></td>
<td valign="top"><a href="#member">Member</a>!</td>
<td>

사용자 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupresult.token">token</strong></td>
<td valign="top"><a href="#authtokenresponse">AuthTokenResponse</a>!</td>
<td>

토큰 정보

</td>
</tr>
</tbody>
</table>

### SigunguModel

시군구

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="sigungumodel.type">type</strong></td>
<td valign="top"><a href="#sigungutypeenum">SigunguTypeEnum</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="sigungumodel.si">si</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="sigungumodel.gungu">gungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### SubscriptionApplyModel

구독중인 상품

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.price">price</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.iscanceled">isCanceled</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

구독 취소 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.canceledat">canceledAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

구독 취소 일시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.expirationdate">expirationDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

구독 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="subscriptionapplymodel.item">item</strong></td>
<td valign="top"><a href="#paymentitemmodel">PaymentItemModel</a>!</td>
<td>

구독항목

</td>
</tr>
</tbody>
</table>

### UserAllow

동의항목

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userallow.geolocation">geolocation</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

위치기반서비스 이용약관 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userallow.thirdparty">thirdParty</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

제3자 정보제공 동의

</td>
</tr>
</tbody>
</table>

### UserBlock

차단 기록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userblock.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblock.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblock.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblock.user">user</strong></td>
<td valign="top"><a href="#user">User</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### UserBlockEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userblockedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblockedge.node">node</strong></td>
<td valign="top"><a href="#userblock">UserBlock</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### UserBlockList

차단 기록 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userblocklist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblocklist.edges">edges</strong></td>
<td valign="top">[<a href="#userblockedge">UserBlockEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userblocklist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### UserDashboardForAdmin

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.membercount">memberCount</strong></td>
<td valign="top"><a href="#membercount">MemberCount</a>!</td>
<td>

가입 회원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.subscribedmembercount">subscribedMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

구독 회원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.pointpurchasedmembercount">pointPurchasedMemberCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 구매 회원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.todaysignupcount">todaySignUpCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

당일 가입 회원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.todaywithdrawalcount">todayWithdrawalCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

당일 탈퇴 회원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.todayviews">todayViews</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

당일 방문자 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userdashboardforadmin.totalviews">totalViews</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

전체 방문자 수

</td>
</tr>
</tbody>
</table>

### UserEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="useredge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="useredge.node">node</strong></td>
<td valign="top"><a href="#user">User</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### UserFCMToken

사용자 FCM 토큰

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.fcmregistrationtoken">fcmRegistrationToken</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

FCM 등록 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.os">os</strong></td>
<td valign="top"><a href="#fcmtokenosenum">FcmTokenOsEnum</a>!</td>
<td>

OS

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtoken.user">user</strong></td>
<td valign="top"><a href="#user">User</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### UserFCMTokenEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtokenedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtokenedge.node">node</strong></td>
<td valign="top"><a href="#userfcmtoken">UserFCMToken</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### UserList

사용자 목록

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userlist.totalcount">totalCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

전체 데이터 개 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userlist.edges">edges</strong></td>
<td valign="top">[<a href="#useredge">UserEdge</a>]!</td>
<td>

페이지네이션된 데이터 목록

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userlist.pageinfo">pageInfo</strong></td>
<td valign="top"><a href="#pageinfo">PageInfo</a>!</td>
<td>

페이지네이션된 페이지 정보

</td>
</tr>
</tbody>
</table>

### UserNotificationSetting

사용자 알림 설정

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.marketing">marketing</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

마케팅 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.keyword">keyword</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

키워드 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.notice">notice</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

공지사항 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.chat">chat</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

채팅 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.follow">follow</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

팔로우 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.communitypost">communityPost</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 게시글 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.communitycommend">communityCommend</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

커뮤니티 댓글 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.locationrange">locationRange</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내 지역 범위로 받기

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.categoryrange">categoryRange</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

내 업종으로 받기

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsetting.kakaotalk">kakaotalk</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

카카오톡으로 받기

</td>
</tr>
</tbody>
</table>

### UserProfile

사용자 프로필

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a>!</td>
<td>

프로필 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.uniqueid">uniqueId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유아이디, 프로필 완성시 결정됨

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.isnicecertified">isNICECertified</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나이스 인증 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.progress">progress</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.user">user</strong></td>
<td valign="top"><a href="#user">User</a></td>
<td>

유저

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.rating">rating</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

평점

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.info">info</strong></td>
<td valign="top"><a href="#profileinfo">ProfileInfo</a>!</td>
<td>

내 프로필 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.rateofcreation">rateOfCreation</strong> ⚠️</td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

프로필 작성률

<p>⚠️ <strong>DEPRECATED</strong></p>
<blockquote>

프론트에서 계산

</blockquote>
</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.isview">isView</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

열람 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.isviewedfinancialinfo">isViewedFinancialInfo</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

재무 정보 열람 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.isfavorite">isFavorite</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

관심 등록 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.canread">canRead</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

기업 정보 열람 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.canissue">canIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

총괄 기업 보고서 발급 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofile.isregistfinancial">isRegistFinancial</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

재무,신용평가,소송 등록 여부

</td>
</tr>
</tbody>
</table>

### UserProfileEdge

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofileedge.cursor">cursor</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커서

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileedge.node">node</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a>!</td>
<td>

노드

</td>
</tr>
</tbody>
</table>

### UserSocialLink

사용자 소셜 서비스 연결

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="usersociallink.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usersociallink.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usersociallink.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usersociallink.socialtype">socialType</strong></td>
<td valign="top"><a href="#usersocialtype">UserSocialType</a>!</td>
<td>

소셜 서비스 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usersociallink.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
</tbody>
</table>

## Inputs

### AdminPostCategoryCreateInput

관리자 게시물 카테고리 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategorycreateinput.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategorycreateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategorycreateinput.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

공개 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategorycreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선 순위

</td>
</tr>
</tbody>
</table>

### AdminPostCategoryUpdateInput

관리자 게시물 카테고리 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategoryupdateinput.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a></td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategoryupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategoryupdateinput.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

공개 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostcategoryupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선 순위

</td>
</tr>
</tbody>
</table>

### AdminPostFilterInput

관리자가 올린 게시물 필터 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.type">type</strong></td>
<td valign="top">[<a href="#adminposttypefilterinput">AdminPostTypeFilterInput</a>!]</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.state">state</strong></td>
<td valign="top">[<a href="#adminpoststatefilterinput">AdminPostStateFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostfilterinput.category__id">category__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

카테고리 ID

</td>
</tr>
</tbody>
</table>

### AdminPostSortInput

관리자가 올린 게시물 정렬 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.type">type</strong></td>
<td valign="top"><a href="#adminposttypesortinput">AdminPostTypeSortInput</a></td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.category__id">category__id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.category__name">category__name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.priority">priority</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

게시 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpostsortinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

게시 종료일

</td>
</tr>
</tbody>
</table>

### AdminPostStateFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpoststatefilterinput.value">value</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpoststatefilterinput.values">values</strong></td>
<td valign="top">[<a href="#adminpoststate">AdminPostState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpoststatefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AdminPostTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypefilterinput.value">value</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#adminposttype">AdminPostType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AdminPostTypeSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypesortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypesortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminposttypesortinput.case">case</strong></td>
<td valign="top">[<a href="#adminposttype">AdminPostType</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### AdvertisementCreateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.location">location</strong></td>
<td valign="top"><a href="#advertisementlocationenum">AdvertisementLocationEnum</a>!</td>
<td>

위치

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.state">state</strong></td>
<td valign="top"><a href="#advertisementstateenum">AdvertisementStateEnum</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.image__id">image__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.mobileimage__id">mobileImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

모바일 이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementcreateinput.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

url

</td>
</tr>
</tbody>
</table>

### AdvertisementFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.location">location</strong></td>
<td valign="top">[<a href="#advertisementlocationenumfilterinput">AdvertisementLocationEnumFilterInput</a>!]</td>
<td>

위치

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.state">state</strong></td>
<td valign="top">[<a href="#advertisementstateenumfilterinput">AdvertisementStateEnumFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.startdate">startDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementfilterinput.enddate">endDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

종료일

</td>
</tr>
</tbody>
</table>

### AdvertisementLocationEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlocationenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#advertisementlocationenum">AdvertisementLocationEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlocationenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#advertisementlocationenum">AdvertisementLocationEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementlocationenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AdvertisementSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.startdate">startDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementsortinput.enddate">endDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

종료일

</td>
</tr>
</tbody>
</table>

### AdvertisementStateEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementstateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#advertisementstateenum">AdvertisementStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementstateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#advertisementstateenum">AdvertisementStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementstateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AdvertisementUpdateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.location">location</strong></td>
<td valign="top"><a href="#advertisementlocationenum">AdvertisementLocationEnum</a></td>
<td>

위치

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.state">state</strong></td>
<td valign="top"><a href="#advertisementstateenum">AdvertisementStateEnum</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.image__id">image__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.mobileimage__id">mobileImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

모바일 이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="advertisementupdateinput.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

url

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyCreateInput

입찰 참여 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplycreateinput.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplycreateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplycreateinput.estimatedamount">estimatedAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

최종 견적 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplycreateinput.estimatefileids">estimateFileIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

견적서 파일 ID

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyFilterInput

입찰 참여 리스트 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.managername">managerName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.phonenumber">phoneNumber</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

담당자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.estimatedamount">estimatedAmount</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

최종 견적 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.state">state</strong></td>
<td valign="top">[<a href="#announcementapplystatefilter">AnnouncementApplyStateFilter</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.userid">userId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

유저 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.user__name">user__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

유저 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.user__email">user__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

유저 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplyfilterinput.announcementid">announcementId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰공고 ID

</td>
</tr>
</tbody>
</table>

### AnnouncementApplySortInput

입찰 신청 리스트 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplysortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplysortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplysortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplysortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplysortinput.estimatedamount">estimatedAmount</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

최종 견적 금액

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyStateFilter

입찰 참여 상태 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplystatefilter.value">value</strong></td>
<td valign="top"><a href="#announcementapplystateenum">AnnouncementApplyStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplystatefilter.values">values</strong></td>
<td valign="top">[<a href="#announcementapplystateenum">AnnouncementApplyStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementapplystatefilter.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementCreateInput

공고 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.mainimage__id">mainImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

메인이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.categories__ids">categories__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.images__ids">images__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.files__ids">files__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a>!</td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a>!</td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a>!</td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a>!</td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a>!</td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.license__ids">license__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

필요 면허 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a>!</td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementcreateinput.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

긴급 공사 여부

</td>
</tr>
</tbody>
</table>

### AnnouncementFieldInfoFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementfieldinfofilterinput.value">value</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfieldinfofilterinput.values">values</strong></td>
<td valign="top">[<a href="#announcementfieldinfo">AnnouncementFieldInfo</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfieldinfofilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementFilterInput

공고 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.workscope">workScope</strong></td>
<td valign="top">[<a href="#announcementworkscopeenumfilterinput">AnnouncementWorkScopeEnumFilterInput</a>!]</td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.workscopeetc">workScopeEtc</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.ordertype">orderType</strong></td>
<td valign="top">[<a href="#announcementordertypefilterinput">AnnouncementOrderTypeFilterInput</a>!]</td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.fieldinfo">fieldInfo</strong></td>
<td valign="top">[<a href="#announcementfieldinfofilterinput">AnnouncementFieldInfoFilterInput</a>!]</td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.type">type</strong></td>
<td valign="top">[<a href="#announcementtypefilterinput">AnnouncementTypeFilterInput</a>!]</td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.worktype">workType</strong></td>
<td valign="top">[<a href="#announcementworktypefilterinput">AnnouncementWorkTypeFilterInput</a>!]</td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.worktypeetc">workTypeEtc</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.uniqueid">uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

공고 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.profile__uniqueid">profile__uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

프로필 고유번호(게시번호)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.profile__companyname">profile__companyName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

상호명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.categories__id">categories__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.categories__name">categories__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.user__id">user__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

게시자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.address">address</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.sigungu">sigungu</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

시군구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.addressdetail">addressDetail</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.servicepricestart">servicePriceStart</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.servicepriceend">servicePriceEnd</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.state">state</strong></td>
<td valign="top">[<a href="#announcementstatefilterinput">AnnouncementStateFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.servicepricetype">servicePriceType</strong></td>
<td valign="top">[<a href="#portfolioservicepricetypefilter">PortfolioServicePriceTypeFilter</a>!]</td>
<td>

참여금 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementfilterinput.postingendat">postingEndAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

공고 게시 종료일

</td>
</tr>
</tbody>
</table>

### AnnouncementOrderTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementordertypefilterinput.value">value</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementordertypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#announcementordertype">AnnouncementOrderType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementordertypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementSortInput

공고 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.servicepriceend">servicePriceEnd</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.sort__duedate">sort__duedate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

마감일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.postingendat">postingEndAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

마감일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.favorite__createdat">favorite__createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

관심등록일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementsortinput.state">state</strong></td>
<td valign="top"><a href="#announcementstatesortinput">AnnouncementStateSortInput</a></td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### AnnouncementStateFilterInput

공고 상태 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatefilterinput.value">value</strong></td>
<td valign="top"><a href="#announcementstateenum">AnnouncementStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatefilterinput.values">values</strong></td>
<td valign="top">[<a href="#announcementstateenum">AnnouncementStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementStateSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatesortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatesortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementstatesortinput.case">case</strong></td>
<td valign="top">[<a href="#announcementstateenum">AnnouncementStateEnum</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementTempCreateInput

임시 공고 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.step">step</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

스텝

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.mainimage__id">mainImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

메인 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.categories__ids">categories__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.images__ids">images__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.files__ids">files__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.license__ids">license__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

필요 면허 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempcreateinput.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

긴급 공사 여부

</td>
</tr>
</tbody>
</table>

### AnnouncementTempFilterInput

임시 공고 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.categories__id">categories__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.sigungu">sigungu</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

시군구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.profile__uniqueid">profile__uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

프로필 고유번호(게시번호)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.user__id">user__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

게시자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.address">address</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.addressdetail">addressDetail</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.servicepricestart">servicePriceStart</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempfilterinput.servicepriceend">servicePriceEnd</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
</tbody>
</table>

### AnnouncementTempSortInput

임시 공고 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempsortinput.servicepriceend">servicePriceEnd</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementTempUpdateInput

임시 공사 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.step">step</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

스텝

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.mainimage__id">mainImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

메인 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.categories__ids">categories__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.images__ids">images__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.files__ids">files__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.license__ids">license__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

필요 면허 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtempupdateinput.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

긴급 공사 여부

</td>
</tr>
</tbody>
</table>

### AnnouncementTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementtypefilterinput.value">value</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#profiletypeenum">ProfileTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementtypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementUpdateInput

공사 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.mainimage__id">mainImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

메인이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.categories__ids">categories__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.images__ids">images__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.files__ids">files__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.license__ids">license__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

필요 면허 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinput.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
</tbody>
</table>

### AnnouncementUpdateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.mainimage__id">mainImage__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

메인이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.categories__ids">categories__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.images__ids">images__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.files__ids">files__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

첨부파일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.worktype">workType</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td>

공사 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.worktypeetc">workTypeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 유형 기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.ordertype">orderType</strong></td>
<td valign="top"><a href="#announcementordertype">AnnouncementOrderType</a></td>
<td>

발주 형태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.fieldinfo">fieldInfo</strong></td>
<td valign="top"><a href="#announcementfieldinfo">AnnouncementFieldInfo</a></td>
<td>

현장 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.fieldinfoetc">fieldInfoEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장정보 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

현장 주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.workscope">workScope</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td>

공사 범위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.workscopeetc">workScopeEtc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공사 범위 기타,

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.haslicense">hasLicense</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

면허 필요 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.license__ids">license__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

필요 면허 리스트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.ispossibletaxbillissue">isPossibleTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.isreqrentledgersubmitpossible">isReqRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 요청 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

작업 내용 서술 입력

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.workstartsoon">workStartSoon</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작업 예상 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.postingday">postingDay</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

선택한 공고 게시일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액 - 직접기재

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.publishername">publisherName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

게시자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.emergencycontact">emergencyContact</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비상 연락처

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.noticetxt">noticeTxt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

공지사항

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.isemergency">isEmergency</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

긴급 공사 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementupdateinputforadmin.state">state</strong></td>
<td valign="top"><a href="#announcementstateenum">AnnouncementStateEnum</a></td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### AnnouncementWorkScopeEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementworkscopeenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementworkscopeenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#announcementworkscopeenum">AnnouncementWorkScopeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementworkscopeenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### AnnouncementWorkTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="announcementworktypefilterinput.value">value</strong></td>
<td valign="top"><a href="#announcementworktype">AnnouncementWorkType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementworktypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#announcementworktype">AnnouncementWorkType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="announcementworktypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### BankCodeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bankcodefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodefilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodefilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### BankCodeSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bankcodesortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodesortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodesortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodesortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bankcodesortinput.name">name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### BannerCreateInput

배너 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannercreateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### BannerUpdateInput

배너 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a></td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="bannerupdateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### BooleanFilterInput

논리(Boolean) 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="booleanfilterinput.value">value</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="booleanfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#booleanfilteroperators">BooleanFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CRIFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crifilterinput.priority">priority</strong></td>
<td valign="top">[<a href="#cripriorityenumfilterinput">CRIPriorityEnumFilterInput</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### CRIPriorityEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="cripriorityenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#cripriorityenum">CRIPriorityEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="cripriorityenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#numberfilteroperators">NumberFilterOperators</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="cripriorityenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#cripriorityenum">CRIPriorityEnum</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### CRISortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="crisortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crisortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crisortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crisortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="crisortinput.name">name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td></td>
</tr>
</tbody>
</table>

### CategoryCreateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorycreateinputforadmin.type">type</strong></td>
<td valign="top"><a href="#categorytypeenum">CategoryTypeEnum</a>!</td>
<td>

분류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorycreateinputforadmin.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorycreateinputforadmin.code">code</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

분류 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorycreateinputforadmin.parentid">parentId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

상위 카테고리 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorycreateinputforadmin.kisccodes">kiscCodes</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

한국표준산업분류 코드

</td>
</tr>
</tbody>
</table>

### CategoryFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinput.value">value</strong></td>
<td valign="top"><a href="#reportcategoryenumtype">ReportCategoryEnumType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinput.values">values</strong></td>
<td valign="top">[<a href="#reportcategoryenumtype">ReportCategoryEnumType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CategoryFilterInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.type">type</strong></td>
<td valign="top">[<a href="#categorytypeenumfilterinput">CategoryTypeEnumFilterInput</a>!]</td>
<td>

분류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryfilterinputforadmin.code">code</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

분류 코드

</td>
</tr>
</tbody>
</table>

### CategorySortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.name">name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorysortinput.code">code</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

분류 코드

</td>
</tr>
</tbody>
</table>

### CategoryTypeEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categorytypeenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#categorytypeenum">CategoryTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorytypeenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#categorytypeenum">CategoryTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categorytypeenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CategoryUpdateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="categoryupdateinputforadmin.type">type</strong></td>
<td valign="top"><a href="#categorytypeenum">CategoryTypeEnum</a></td>
<td>

분류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryupdateinputforadmin.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryupdateinputforadmin.code">code</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

분류 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryupdateinputforadmin.parentid">parentId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

상위 카테고리 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="categoryupdateinputforadmin.kisccodes">kiscCodes</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

한국표준산업분류 코드

</td>
</tr>
</tbody>
</table>

### CommunityCategoryCreateInput

커뮤니티 카테고리 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategorycreateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커뮤니티 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategorycreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

커뮤니티 카테고리 배치 순서

</td>
</tr>
</tbody>
</table>

### CommunityCategoryFilterInput

커뮤니티 카테고리 필터링

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryfilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### CommunityCategoryOrderByInput

커뮤니티 카테고리 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.name">name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryorderbyinput.priority">priority</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

순서

</td>
</tr>
</tbody>
</table>

### CommunityCategoryUpdateInput

커뮤니티 카테고리 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

커뮤니티 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitycategoryupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

커뮤니티 카테고리 배치 순서

</td>
</tr>
</tbody>
</table>

### CommunityPostCreateInput

커뮤니티 게시물 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.addressname">addressName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.category__id">category__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

커뮤니티 카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.file__ids">file__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

게시물 파일들

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.hashtags">hashtags</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

해시태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostcreateinput.usertag__ids">usertag__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사용자 ID

</td>
</tr>
</tbody>
</table>

### CommunityPostFilterInput

커뮤니티 게시물 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

게시물 제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.content">content</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

게시물 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.addressname">addressName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.addressdetail">addressDetail</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.isvisible">isVisible</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

숨김여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.author__id">author__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.author__name">author__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.author__email">author__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.category__id">category__id</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

카테고리 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.category__name">category__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.hashtags__keyword">hashtags__keyword</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

해시태그 키워드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.usertags__name">usertags__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

태그된 사용자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.likes__id">likes__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

좋아요 사용자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.ispinned">isPinned</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

상단 고정 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostfilterinput.hide__id">hide__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

숨기기한 사용자 고유 id

</td>
</tr>
</tbody>
</table>

### CommunityPostOrderByInput

커뮤니티 게시물 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.viewcount">viewCount</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

조회수 정렬

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.likecount">likeCount</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

좋아요수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.replycount">replyCount</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

댓글수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostorderbyinput.pinnedat">pinnedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

상단 고정된 날짜

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyCreateInput

커뮤니티 게시물 댓글 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplycreateinput.post__id">post__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

게시물 uuid (댓글일 경우만)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplycreateinput.parent__id">parent__id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

상위 댓글 uuid (대댓글일 경우만)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplycreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

댓글 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplycreateinput.usertag__ids">usertag__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사용자 ID

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyFilterInput

커뮤니티 게시물 댓글 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.post__id">post__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

관련 게시물 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.parent__id">parent__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

대댓글일 경우 상위 댓글 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.author__id">author__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.content">content</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

댓글 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.usertags__name">usertags__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

태그된 사용자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyfilterinput.usertags__id">usertags__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

태그된 사용자 uuid

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyOrderByInput

커뮤니티 게시물 댓글 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyorderbyinput.content">content</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

댓글 내용 정렬

</td>
</tr>
</tbody>
</table>

### CommunityPostReplyUpdateInput

커뮤니티 게시물 댓글 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

댓글 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostreplyupdateinput.usertag__ids">usertag__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사용자 ID

</td>
</tr>
</tbody>
</table>

### CommunityPostUpdateInput

커뮤니티 게시물 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.addressname">addressName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.hashtags">hashtags</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

해시태그

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.usertag__ids">usertag__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사용자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

보이기 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communitypostupdateinput.hashtag">hashtag</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

게시물 내 해시태그 키워드 모두

</td>
</tr>
</tbody>
</table>

### CommunityReportCategoryFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcategoryfilterinput.value">value</strong></td>
<td valign="top"><a href="#communityreportcategoryenumtype">CommunityReportCategoryEnumType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcategoryfilterinput.values">values</strong></td>
<td valign="top">[<a href="#communityreportcategoryenumtype">CommunityReportCategoryEnumType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcategoryfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CommunityReportCreateInput

커뮤니티 신고 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.targetid">targetId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 커뮤니티 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.category">category</strong></td>
<td valign="top"><a href="#communityreportcategoryenumtype">CommunityReportCategoryEnumType</a></td>
<td>

신고 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.etc">etc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

기타 예비용 필드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.type">type</strong></td>
<td valign="top"><a href="#communityreporttype">CommunityReportType</a></td>
<td>

신고 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportcreateinput.file__ids">file__ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

게시물 파일들

</td>
</tr>
</tbody>
</table>

### CommunityReportFilterInput

커뮤니티 신고 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.content">content</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

신고 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.author__id">author__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.author__name">author__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.author__email">author__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.etc">etc</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

기타

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.type">type</strong></td>
<td valign="top">[<a href="#communityreporttypefilterinput">CommunityReportTypeFilterInput</a>!]</td>
<td>

신고 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.category">category</strong></td>
<td valign="top">[<a href="#communityreportcategoryfilterinput">CommunityReportCategoryFilterInput</a>!]</td>
<td>

신고 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportfilterinput.state">state</strong></td>
<td valign="top">[<a href="#communityreportstatefilterinput">CommunityReportStateFilterInput</a>!]</td>
<td>

신고 상태

</td>
</tr>
</tbody>
</table>

### CommunityReportOrderByInput

커뮤니티 신고 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### CommunityReportStateFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportstatefilterinput.value">value</strong></td>
<td valign="top"><a href="#communityreportstateenumtype">CommunityReportStateEnumType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportstatefilterinput.values">values</strong></td>
<td valign="top">[<a href="#communityreportstateenumtype">CommunityReportStateEnumType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportstatefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CommunityReportTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreporttypefilterinput.value">value</strong></td>
<td valign="top"><a href="#communityreporttype">CommunityReportType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreporttypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#communityreporttype">CommunityReportType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreporttypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### CommunityReportUpdateInput

커뮤니티 신고 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="communityreportupdateinput.targetid">targetId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 커뮤니티 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

신고 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportupdateinput.category">category</strong></td>
<td valign="top"><a href="#communityreportcategoryenumtype">CommunityReportCategoryEnumType</a></td>
<td>

신고 카테고리

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportupdateinput.etc">etc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

기타 예비용 필드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="communityreportupdateinput.type">type</strong></td>
<td valign="top"><a href="#communityreporttype">CommunityReportType</a></td>
<td>

신고 종류

</td>
</tr>
</tbody>
</table>

### CompanyInfoFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

회사명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfofilterinput.businessregistrationnumber">businessRegistrationNumber</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

사업자등록번호

</td>
</tr>
</tbody>
</table>

### CompanyInfoSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="companyinfosortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfosortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfosortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="companyinfosortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### DateTimeFilterInput

날짜(DateTime) 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="datetimefilterinput.value">value</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="datetimefilterinput.value2">value2</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="datetimefilterinput.values">values</strong></td>
<td valign="top">[<a href="#datetime">DateTime</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="datetimefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#numberfilteroperators">NumberFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### EnterpriseFilterInput

업체 리스트 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.cripriority">criPriority</strong></td>
<td valign="top">[<a href="#cripriorityenumfilterinput">CRIPriorityEnumFilterInput</a>!]</td>
<td>

cri 필터

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.license__id">license__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

면허 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.license__name">license__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

면허명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.companytype">companyType</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

업태업종 및 면허

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.addresses">addresses</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.sigungu">sigungu</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

시군구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.type">type</strong></td>
<td valign="top">[<a href="#profiletypefilterinput">ProfileTypeFilterInput</a>!]</td>
<td>

업체 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.uniqueid">uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

고유번

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.companyname">companyName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

업체명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.reviewscore">reviewScore</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.salesamount">salesAmount</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

매출액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.mainbusiness">mainBusiness</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주력사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisefilterinput.users__name">users__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

사용자 이름

</td>
</tr>
</tbody>
</table>

### EnterpriseSortInput

업체 리스트 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.reviewscore">reviewScore</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="enterprisesortinput.log__createdat">log__createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

관심등록일

</td>
</tr>
</tbody>
</table>

### EventCreateInput

이벤트 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventcreateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### EventUpdateInput

이벤트 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a></td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="eventupdateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### FaqCreateInput

자주 묻는 질문 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="faqcreateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqcreateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqcreateinput.question">question</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

질문

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqcreateinput.answer">answer</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

답변

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqcreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
</tbody>
</table>

### FaqUpdateInput

자주 묻는 질문 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="faqupdateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqupdateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqupdateinput.question">question</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

질문

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqupdateinput.answer">answer</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

답변

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="faqupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
</tbody>
</table>

### FloatFilterInput

소수(Float) 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="floatfilterinput.value">value</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="floatfilterinput.value2">value2</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="floatfilterinput.values">values</strong></td>
<td valign="top">[<a href="#float">Float</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="floatfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#numberfilteroperators">NumberFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### IDFilterInput

ID 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="idfilterinput.value">value</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="idfilterinput.values">values</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="idfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#idfilteroperators">IDFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### InquireCreateInput

문의하기 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquirecreateinput.type">type</strong></td>
<td valign="top"><a href="#inquiretype">InquireType</a></td>
<td>

문의 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirecreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirecreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirecreateinput.fileids">fileIds</strong></td>
<td valign="top">[<a href="#id">ID</a>]</td>
<td></td>
</tr>
</tbody>
</table>

### InquireFilterInput

문의하기 필터링

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.type">type</strong></td>
<td valign="top">[<a href="#inquiretypefilterinput">InquireTypeFilterInput</a>!]</td>
<td>

문의 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.content">content</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.state">state</strong></td>
<td valign="top">[<a href="#inquirestatefilterinput">InquireStateFilterInput</a>!]</td>
<td>

문의 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.answercontent">answerContent</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

답변

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirefilterinput.answereddat">answereddAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

답변일

</td>
</tr>
</tbody>
</table>

### InquireSortInput

문의하기 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquiresortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquiresortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquiresortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquiresortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### InquireStateFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquirestatefilterinput.value">value</strong></td>
<td valign="top"><a href="#inquirestate">InquireState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirestatefilterinput.values">values</strong></td>
<td valign="top">[<a href="#inquirestate">InquireState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquirestatefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### InquireTypeFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquiretypefilterinput.value">value</strong></td>
<td valign="top"><a href="#inquiretype">InquireType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquiretypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#inquiretype">InquireType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquiretypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### InquireUpdateInput

문의하기 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquireupdateinput.type">type</strong></td>
<td valign="top"><a href="#inquiretype">InquireType</a></td>
<td>

문의 종류

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquireupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquireupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="inquireupdateinput.fileids">fileIds</strong></td>
<td valign="top">[<a href="#id">ID</a>]</td>
<td></td>
</tr>
</tbody>
</table>

### InquireUpdateInputForAdmin

문의하기 수정 - 관리자용

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="inquireupdateinputforadmin.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자 메모

</td>
</tr>
</tbody>
</table>

### IntFilterInput

정수(Int) 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="intfilterinput.value">value</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="intfilterinput.value2">value2</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="intfilterinput.values">values</strong></td>
<td valign="top">[<a href="#float">Float</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="intfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#numberfilteroperators">NumberFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### IntSortInput

정수 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="intsortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="intsortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="intsortinput.case">case</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### ItemTypeEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="itemtypeenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#paymentitemtypeenum">PaymentItemTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="itemtypeenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#paymentitemtypeenum">PaymentItemTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="itemtypeenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### LicenseFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="licensefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensefilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensefilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### LicenseSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="licensesortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensesortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensesortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensesortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="licensesortinput.name">name</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td></td>
</tr>
</tbody>
</table>

### MatchPostCategoryCreateInput

매칭 카테고리 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategorycreateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

매칭 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategorycreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

매칭 카테고리 배치 순서

</td>
</tr>
</tbody>
</table>

### MatchPostCategoryFilterInput

매칭 카테고리 필터링

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryfilterinput.isfavorite">isFavorite</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

즐겨찾기 여부

</td>
</tr>
</tbody>
</table>

### MatchPostCategoryOrderByInput

매칭 카테고리 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.name">name</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryorderbyinput.priority">priority</strong></td>
<td valign="top"><a href="#intsortinput">IntSortInput</a></td>
<td>

순서

</td>
</tr>
</tbody>
</table>

### MatchPostCategoryUpdateInput

매칭 카테고리 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

매칭 카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostcategoryupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

매칭 카테고리 배치 순서

</td>
</tr>
</tbody>
</table>

### MatchPostFilterInput

매칭 게시물 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.description">description</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

설명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.addressname">addressName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 명칭

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.addresssido">addressSiDo</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 시,도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.addresssigungu">addressSiGunGu</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 시,군,구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.addressdetail">addressDetail</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.isvisible">isVisible</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

숨김여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.state">state</strong></td>
<td valign="top">[<a href="#matchpoststateenumfilterinput">MatchPostStateEnumFilterInput</a>!]</td>
<td>

매칭 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.viewcount">viewCount</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

조회수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.likecount">likeCount</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

좋아요수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.replycount">replyCount</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

댓글수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.likes__id">likes__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

좋아요 사용자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.author__id">author__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.author__name">author__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.author__email">author__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

작성자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.trader__id">trader__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

거래 대상자 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.trader__name">trader__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

거래 대상자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.trader__email">trader__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

거래 대상자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.type__id">type__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

게시물 타입 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.type__name">type__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

게시물 타입 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.category__id">category__id</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

카테고리 고유 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.category__name">category__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

카테고리 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostfilterinput.usertags__name">usertags__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

태그된 사용자 이름

</td>
</tr>
</tbody>
</table>

### MatchPostOrderByInput

매칭 게시물 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.viewcount">viewCount</strong></td>
<td valign="top"><a href="#intsortinput">IntSortInput</a></td>
<td>

조회수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.likecount">likeCount</strong></td>
<td valign="top"><a href="#intsortinput">IntSortInput</a></td>
<td>

좋아요수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpostorderbyinput.replycount">replyCount</strong></td>
<td valign="top"><a href="#intsortinput">IntSortInput</a></td>
<td>

댓글수

</td>
</tr>
</tbody>
</table>

### MatchPostStateEnumFilterInput

매칭 상태 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchpoststateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#matchpoststateenum">MatchPostStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpoststateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#matchpoststateenum">MatchPostStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchpoststateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### MatchPostTypeCreateInput

매칭 게시물 타입 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypecreateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

매칭 게시물 타입 이름

</td>
</tr>
</tbody>
</table>

### MatchPostTypeFilterInput

매칭 게시물 타입 필터링

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypefilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypefilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### MatchPostTypeOrderByInput

매칭 게시물 타입 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeorderbyinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeorderbyinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeorderbyinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeorderbyinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeorderbyinput.name">name</strong></td>
<td valign="top"><a href="#stringfilterinput">StringFilterInput</a></td>
<td>

이름

</td>
</tr>
</tbody>
</table>

### MatchPostTypeUpdateInput

매칭 게시물 타입 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="matchposttypeupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

매칭 게시물 타입 이름

</td>
</tr>
</tbody>
</table>

### NoticeCreateInput

공지사항 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="noticecreateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticecreateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticecreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticecreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
</tbody>
</table>

### NoticeUpdateInput

공지사항 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="noticeupdateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticeupdateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticeupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="noticeupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
</tbody>
</table>

### NotificationCreateInput

알림 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.message">message</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.type">type</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.relationid">relationId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

연관 데이터의 ID (타입을 참고하여 사용)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크 URL 주소 (타입을 참고하여 사용)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.imageurl">imageURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationcreateinput.recipientids">recipientIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

수신자 ID 목록 (없으면 해당 알림 타입 허용자에게 전부 발송)

</td>
</tr>
</tbody>
</table>

### NotificationFilterInput

알림 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.message">message</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.type">type</strong></td>
<td valign="top">[<a href="#notificationtypefilterinput">NotificationTypeFilterInput</a>!]</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.relationid">relationId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.url">url</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

링크 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.imageurl">imageURL</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.iscreatedforadmin">isCreatedForAdmin</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

관리자 임의 전송 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationfilterinput.recipients__id">recipients__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

수신자 ID

</td>
</tr>
</tbody>
</table>

### NotificationSortInput

알림 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.title">title</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.message">message</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.type">type</strong></td>
<td valign="top"><a href="#notificationtypesortinput">NotificationTypeSortInput</a></td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.relationid">relationId</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.url">url</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

링크 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.imageurl">imageURL</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.iscreatedforadmin">isCreatedForAdmin</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

관리자 임의 전송 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationsortinput.recipients__id">recipients__id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수신자 ID

</td>
</tr>
</tbody>
</table>

### NotificationStorageCreateInput

알림 저장소 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.message">message</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.type">type</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a></td>
<td>

알림 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.relationid">relationId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.imageurl">imageURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이미지  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.target">target</strong></td>
<td valign="top"><a href="#notificationstoragetargettype">NotificationStorageTargetType</a>!</td>
<td>

수신 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragecreateinput.scheduledat">scheduledAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

예약 발송 시간, null이면 즉시

</td>
</tr>
</tbody>
</table>

### NotificationStorageFilterInput

알림 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.title">title</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.message">message</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.type">type</strong></td>
<td valign="top">[<a href="#notificationtypefilterinput">NotificationTypeFilterInput</a>!]</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.relationid">relationId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.url">url</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

링크 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.imageurl">imageURL</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.recipients__id">recipients__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

수신자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.target">target</strong></td>
<td valign="top">[<a href="#notificationstoragetargettype">NotificationStorageTargetType</a>!]</td>
<td>

수신 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.scheduledat">scheduledAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

예약 발송 시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragefilterinput.issend">isSend</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

전송 여부

</td>
</tr>
</tbody>
</table>

### NotificationStorageSortInput

알림 저장소 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.title">title</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.message">message</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

메시지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.type">type</strong></td>
<td valign="top"><a href="#notificationtypesortinput">NotificationTypeSortInput</a></td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.relationid">relationId</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.url">url</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

링크 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.imageurl">imageURL</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

이미지 URL 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.recipients__id">recipients__id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수신자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstoragesortinput.scheduledat">scheduledAt</strong></td>
<td valign="top">[<a href="#sortinput">SortInput</a>!]</td>
<td>

예약 발송 시간

</td>
</tr>
</tbody>
</table>

### NotificationStorageUpdateInput

알림 저장소 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.message">message</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.type">type</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a></td>
<td>

알림 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.relationid">relationId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

연관 데이터의 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.url">url</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

링크  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.imageurl">imageURL</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이미지  URL주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.target">target</strong></td>
<td valign="top"><a href="#notificationstoragetargettype">NotificationStorageTargetType</a></td>
<td>

수신 타겟

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationstorageupdateinput.scheduledat">scheduledAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

예약 발송 시간, null이면 즉시

</td>
</tr>
</tbody>
</table>

### NotificationTypeFilterInput

알림 타입 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypefilterinput.value">value</strong></td>
<td valign="top"><a href="#notificationtype">NotificationType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#notificationtype">NotificationType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### NotificationTypeSortInput

알림 타입 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypesortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypesortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="notificationtypesortinput.case">case</strong></td>
<td valign="top">[<a href="#notificationtype">NotificationType</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### OmitObjectType

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.categories__id">categories__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.sigungu">sigungu</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

시군구

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.profile__uniqueid">profile__uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

프로필 고유번호(게시번호)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.address">address</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.addressdetail">addressDetail</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역 상세

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.servicepricestart">servicePriceStart</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="omitobjecttype.servicepriceend">servicePriceEnd</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

시작 참여금

</td>
</tr>
</tbody>
</table>

### PaymentFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.buyer__name">buyer__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

구매자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.moid">moid</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주문번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.state">state</strong></td>
<td valign="top">[<a href="#paymentstateenumfilterinput">PaymentStateEnumFilterInput</a>!]</td>
<td>

결제 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.subscription__iscanceled">subscription__isCanceled</strong></td>
<td valign="top">[<a href="#booleanfilterinput">BooleanFilterInput</a>!]</td>
<td>

구독 취소 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.subscription__expirationdate">subscription__expirationDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

구독 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.item__type">item__type</strong></td>
<td valign="top">[<a href="#itemtypeenumfilterinput">ItemTypeEnumFilterInput</a>!]</td>
<td>

결제항목 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.profile__type">profile__type</strong></td>
<td valign="top">[<a href="#profiletypefilterinput">ProfileTypeFilterInput</a>!]</td>
<td>

기업 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.profile__companyname">profile__companyName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

상호명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.paymethod">payMethod</strong></td>
<td valign="top">[<a href="#paymentmethodfilterinput">PaymentMethodFilterInput</a>!]</td>
<td>

결제 수단

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentfilterinput.paidat">paidAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

결제 일시

</td>
</tr>
</tbody>
</table>

### PaymentItemCreateInput

결제 충전 항목 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.type">type</strong></td>
<td valign="top"><a href="#paymentitemtypeenum">PaymentItemTypeEnum</a>!</td>
<td>

유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.auth">auth</strong></td>
<td valign="top"><a href="#paymentitemauthenum">PaymentItemAuthEnum</a>!</td>
<td>

구독 권한 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.priority">priority</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

순번

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.freepoint">freePoint</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

무상 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.price">price</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

결제금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemcreateinput.isuse">isUse</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

활용 여부

</td>
</tr>
</tbody>
</table>

### PaymentItemUpdateInput

결제 충전 항목 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.auth">auth</strong></td>
<td valign="top"><a href="#paymentitemauthenum">PaymentItemAuthEnum</a></td>
<td>

구독 권한 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

순번

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.point">point</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.freepoint">freePoint</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

무상 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.price">price</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

결제금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentitemupdateinput.isuse">isUse</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

활용 여부

</td>
</tr>
</tbody>
</table>

### PaymentMethodCreateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodcreateinput.cardnumber">cardNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카드 번호 (숫자만)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodcreateinput.expyear">expYear</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

유효기간(년, YY)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodcreateinput.expmonth">expMonth</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

유효기간(월, MM)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodcreateinput.idnumber">idNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

개인: 생년월일(YYMMDD), 법인: 사업자번호(10자리)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodcreateinput.cardpassword">cardPassword</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

카드 비밀번호 앞 2자리

</td>
</tr>
</tbody>
</table>

### PaymentMethodFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodfilterinput.value">value</strong></td>
<td valign="top"><a href="#paymentmethodenumtype">PaymentMethodEnumType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodfilterinput.values">values</strong></td>
<td valign="top">[<a href="#paymentmethodenumtype">PaymentMethodEnumType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentmethodfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PaymentRefundFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.state">state</strong></td>
<td valign="top">[<a href="#paymentrefundstateenumfilterinput">PaymentRefundStateEnumFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.requestingdate">requestingDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

요청일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundfilterinput.processingdate">processingDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

처리일

</td>
</tr>
</tbody>
</table>

### PaymentRefundSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.requestingdate">requestingDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

요청일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundsortinput.processingdate">processingDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

처리일

</td>
</tr>
</tbody>
</table>

### PaymentRefundStateEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundstateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#paymentrefundstateenum">PaymentRefundStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundstateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#paymentrefundstateenum">PaymentRefundStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentrefundstateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PaymentSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### PaymentStateEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentstateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#paymentstateenumtype">PaymentStateEnumType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentstateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#paymentstateenumtype">PaymentStateEnumType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentstateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PaymentUpdateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="paymentupdateinputforadmin.amount">amount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentupdateinputforadmin.moid">moid</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주문 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="paymentupdateinputforadmin.state">state</strong></td>
<td valign="top"><a href="#paymentstateenumtype">PaymentStateEnumType</a></td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### PointFilterInput

포인트 리스트 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.user__id">user__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.type">type</strong></td>
<td valign="top">[<a href="#pointtypeenumfilterinput">PointTypeEnumFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointfilterinput.reason">reason</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### PointRefundCreateInput

환전 요청 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundcreateinput.bankname">bankName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환전 받을 은행명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundcreateinput.bankowner">bankOwner</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환전 받을 은행 계좌 소유주명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundcreateinput.bankaccount">bankAccount</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환전 받을 은행 계좌

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundcreateinput.reason">reason</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환전 사유

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundcreateinput.amount">amount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

환급 받을 포인트

</td>
</tr>
</tbody>
</table>

### PointRefundFilterInput

포인트 환전 요청 정보 리스트 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.state">state</strong></td>
<td valign="top">[<a href="#pointrefundstateenumfilterinput">PointRefundStateEnumFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.user__id">user__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.user__nickname">user__nickName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.user__name">user__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.profile__type">profile__type</strong></td>
<td valign="top">[<a href="#profiletypefilterinput">ProfileTypeFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.user__email">user__email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.user__phonenumber">user__phoneNumber</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.bankname">bankName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

은행명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.bankowner">bankOwner</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

은행계좌 소유주

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.bankaccount">bankAccount</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

은행계좌

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundfilterinput.amount">amount</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

환급 금액

</td>
</tr>
</tbody>
</table>

### PointRefundSortInput

포인트 환전 요청 정보 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundsortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundsortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
</tbody>
</table>

### PointRefundStateEnumFilterInput

포인트 환전 요청 정보 상태 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundstateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#pointrefundstateenum">PointRefundStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundstateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#pointrefundstateenum">PointRefundStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointrefundstateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PointSortInput

포인트 리스트 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### PointTypeEnumFilterInput

포인트 발생 주체 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="pointtypeenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#pointtypeenum">PointTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointtypeenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#pointtypeenum">PointTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="pointtypeenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PopupCreateInput

팝업 생성 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a>!</td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupcreateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### PopupUpdateInput

팝업 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.categoryid">categoryId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

카테고리 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.title">title</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.action">action</strong></td>
<td valign="top"><a href="#adminpostaction">AdminPostAction</a></td>
<td>

클릭 액션

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.priority">priority</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td>

우선순위

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.coverurl">coverUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

커버 이미지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.publishingperiodstartat">publishingPeriodStartAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 시작일
없을시 1990-01-01 00:00:00.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.publishingperiodendat">publishingPeriodEndAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

게시 종료일
없을시 2999-12-31 23:59:59.000 +0900 으로 생성

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="popupupdateinput.linkurl">linkUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이동 URL

</td>
</tr>
</tbody>
</table>

### PortfolioConstructionTypeFilter

서비스 금액 타입 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfolioconstructiontypefilter.value">value</strong></td>
<td valign="top"><a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioconstructiontypefilter.values">values</strong></td>
<td valign="top">[<a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioconstructiontypefilter.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PortfolioCreateInput

포트폴리오 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.image_ids">image_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

사진 IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.mainimage_id">mainImage_id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

대표 이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.locationsi">locationSi</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.locationdo">locationDo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.category_ids">category_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]!</td>
<td>

업종(제공된 서비스 항목) IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.constructiontype">constructionType</strong></td>
<td valign="top"><a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a>!</td>
<td>

공사 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.projectsize">projectSize</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

프로젝트 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a>!</td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

서비스 금액이 직접기재시 서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.servicetermstart">serviceTermStart</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

서비스 기간 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.servicetermend">serviceTermEnd</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

서비스 기간 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliocreateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

제공 서비스 상세 설명

</td>
</tr>
</tbody>
</table>

### PortfolioFilterInput

포트폴리오 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.locationsi">locationSi</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역 시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.locationdo">locationDo</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

지역 도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.projectsize">projectSize</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

프로젝트 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.servicepricetype">servicePriceType</strong></td>
<td valign="top">[<a href="#portfolioservicepricetypefilter">PortfolioServicePriceTypeFilter</a>!]</td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.serviceprice">servicePrice</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

서비스 금액이 직접기재시 서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.servicepricestart">servicePriceStart</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

서비스 금액 범위 시작값

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.servicepriceend">servicePriceEnd</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

서비스 금액 범위 끝값

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.servicetermstart">serviceTermStart</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

서비스 기간 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.servicetermend">serviceTermEnd</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

서비스 기간 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.categories__id">categories__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.categories__name">categories__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.user__id">user__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.constructiontype">constructionType</strong></td>
<td valign="top">[<a href="#portfolioconstructiontypefilter">PortfolioConstructionTypeFilter</a>!]</td>
<td>

공사 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.profile__companyname">profile__companyName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

회사명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.license__name">license__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

면허명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliofilterinput.profile__criname">profile__criName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

신용등급

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationCreateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationcreateinput.portfolioid">portfolioId</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

프토플리오 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationcreateinput.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationcreateinput.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationcreateinput.state">state</strong></td>
<td valign="top"><a href="#portfoliorecommendationstateenum">PortfolioRecommendationStateEnum</a></td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.startdate">startDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.enddate">endDate</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.portfolio__id">portfolio__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

포트폴리오 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationfilterinput.state">state</strong></td>
<td valign="top">[<a href="#portfoliorecommendationstateenumfilterinput">PortfolioRecommendationStateEnumFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationSortInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.startdate">startDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationsortinput.enddate">endDate</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

종료일

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationStateEnumFilterInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationstateenumfilterinput.value">value</strong></td>
<td valign="top"><a href="#portfoliorecommendationstateenum">PortfolioRecommendationStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationstateenumfilterinput.values">values</strong></td>
<td valign="top">[<a href="#portfoliorecommendationstateenum">PortfolioRecommendationStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationstateenumfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PortfolioRecommendationUpdateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationupdateinput.startdate">startDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationupdateinput.enddate">endDate</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliorecommendationupdateinput.state">state</strong></td>
<td valign="top"><a href="#portfoliorecommendationstateenum">PortfolioRecommendationStateEnum</a></td>
<td>

상태

</td>
</tr>
</tbody>
</table>

### PortfolioServicePriceTypeFilter

서비스 금액 타입 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfolioservicepricetypefilter.value">value</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioservicepricetypefilter.values">values</strong></td>
<td valign="top">[<a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioservicepricetypefilter.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PortfolioSortInput

포트폴리오 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfoliosortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliosortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliosortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliosortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfoliosortinput.favorite__createdat">favorite__createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

관심등록일

</td>
</tr>
</tbody>
</table>

### PortfolioUpdateInput

포트폴리오 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.image_ids">image_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진 IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.mainimage_id">mainImage_id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

대표 이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.locationsi">locationSi</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.locationdo">locationDo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.category_ids">category_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종(제공된 서비스 항목) IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.constructiontype">constructionType</strong></td>
<td valign="top"><a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a></td>
<td>

공사 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.projectsize">projectSize</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

프로젝트 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액이 직접기재시 서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.servicetermstart">serviceTermStart</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

서비스 기간 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.servicetermend">serviceTermEnd</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

서비스 기간 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제공 서비스 상세 설명

</td>
</tr>
</tbody>
</table>

### PortfolioUpdateInputForAdmin

포트폴리오 수정 - 관리자

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.image_ids">image_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

사진 IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.mainimage_id">mainImage_id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

대표 이미지 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.locationsi">locationSi</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 시

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.locationdo">locationDo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

지역 도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.category_ids">category_ids</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

업종(제공된 서비스 항목) IDs

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.constructiontype">constructionType</strong></td>
<td valign="top"><a href="#portfolioconstructiontypeenum">PortfolioConstructionTypeEnum</a></td>
<td>

공사 구분

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.projectsize">projectSize</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

프로젝트 규모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.servicepricetype">servicePriceType</strong></td>
<td valign="top"><a href="#portfolioservicepricetypeenum">PortfolioServicePriceTypeEnum</a></td>
<td>

서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.serviceprice">servicePrice</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

서비스 금액이 직접기재시 서비스 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.servicetermstart">serviceTermStart</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

서비스 기간 시작일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.servicetermend">serviceTermEnd</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

서비스 기간 종료일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제공 서비스 상세 설명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

포트폴리오가 나타나는지 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="portfolioupdateinputforadmin.isrecommended">isRecommended</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

추천 여부

</td>
</tr>
</tbody>
</table>

### ProfileCompanyInfoUpdateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.companycode">companyCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.companytype">companyType</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업태업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.mainbusiness">mainBusiness</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력 사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.phones">phones</strong></td>
<td valign="top">[<a href="#profileinfophoneinput">ProfileInfoPhoneInput</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.addresses">addresses</strong></td>
<td valign="top">[<a href="#profileinfoaddressinput">ProfileInfoAddressInput</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.settleaccountday">settleAccountDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

결산일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.stockholders">stockholders</strong></td>
<td valign="top">[<a href="#profileinfostockholdersinput">ProfileInfoStockholdersInput</a>!]</td>
<td>

주요 주주들

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.managerphonenumber">managerPhoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.manageremail">managerEmail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.licenseids">licenseIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

면허 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profilecompanyinfoupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

로고 id

</td>
</tr>
</tbody>
</table>

### ProfileConsumerInfoUpdateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

로고 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileconsumerinfoupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
</tbody>
</table>

### ProfileEngineerInfoUpdateInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.phones">phones</strong></td>
<td valign="top">[<a href="#profileinfophoneinput">ProfileInfoPhoneInput</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.addresses">addresses</strong></td>
<td valign="top">[<a href="#profileinfoaddressinput">ProfileInfoAddressInput</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileengineerinfoupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

로고 id

</td>
</tr>
</tbody>
</table>

### ProfileInfoAddressInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.sigungu">sigungu</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.postcode">postCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfoaddressinput.isfirst">isFirst</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

첫번째인지(본점)

</td>
</tr>
</tbody>
</table>

### ProfileInfoPhoneInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophoneinput.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophoneinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfophoneinput.isfirst">isFirst</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

첫번째인지(본점)

</td>
</tr>
</tbody>
</table>

### ProfileInfoStockholdersInput

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholdersinput.index">index</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholdersinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profileinfostockholdersinput.rate">rate</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### ProfileTypeFilterInput

업체 유형 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="profiletypefilterinput.value">value</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profiletypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#profiletypeenum">ProfileTypeEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="profiletypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### ReportCreateInput

신고 생성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportcreateinput.targetuserid">targetUserId</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

신고 당하는 사용자 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportcreateinput.category">category</strong></td>
<td valign="top"><a href="#reportcategoryenumtype">ReportCategoryEnumType</a>!</td>
<td>

신고 대상의 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportcreateinput.content">content</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

신고 내용 (500자 이하)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportcreateinput.etc">etc</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비고

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportcreateinput.fileids">fileIds</strong></td>
<td valign="top">[<a href="#id">ID</a>]</td>
<td></td>
</tr>
</tbody>
</table>

### ReportFilterInput

신고 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.author__id">author__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.reporteduser__id">reportedUser__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

신고 당한 사용자 uuid

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportfilterinput.category">category</strong></td>
<td valign="top">[<a href="#categoryfilterinput">CategoryFilterInput</a>!]</td>
<td>

신고 대상의 유형

</td>
</tr>
</tbody>
</table>

### ReportSortInput

신고 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
</tbody>
</table>

### ReportUpdateInput

신고 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reportupdateinput.state">state</strong></td>
<td valign="top"><a href="#reportstateenumtype">ReportStateEnumType</a></td>
<td>

신고 처리 상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reportupdateinput.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자 메모

</td>
</tr>
</tbody>
</table>

### ReviewFilterInput

리뷰 리스트 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.userid">userId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.score">score</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.state">state</strong></td>
<td valign="top">[<a href="#reviewstatefilterinput">ReviewStateFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.announcementid">announcementId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.announcement__userid">announcement__userId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고 작성자 userId

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinput.announcementapplyid">announcementApplyId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고 참여 ID

</td>
</tr>
</tbody>
</table>

### ReviewFilterInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.createdat">createdAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.deletedat">deletedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.updatedat">updatedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.userid">userId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

작성자ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.score">score</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.state">state</strong></td>
<td valign="top">[<a href="#reviewstatefilterinput">ReviewStateFilterInput</a>!]</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcementid">announcementId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcement__userid">announcement__userId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고 작성자 userId

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcementapplyid">announcementApplyId</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

입찰 공고 참여 ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.profile__companyname">profile__companyName</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

상호명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcementcategories__name">announcementCategories__name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

카테고리명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcement__servicepricestart">announcement__servicePriceStart</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

서비스 가격 시작

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcement__servicepriceend">announcement__servicePriceEnd</strong></td>
<td valign="top">[<a href="#floatfilterinput">FloatFilterInput</a>!]</td>
<td>

서비스 가격 종료

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewfilterinputforadmin.announcement__servicepricetype">announcement__servicePriceType</strong></td>
<td valign="top">[<a href="#portfolioservicepricetypefilter">PortfolioServicePriceTypeFilter</a>!]</td>
<td>

참여금 타입

</td>
</tr>
</tbody>
</table>

### ReviewSortInput

리뷰 리스트 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewsortinput.id">id</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewsortinput.createdat">createdAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewsortinput.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewsortinput.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewsortinput.score">score</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

점수

</td>
</tr>
</tbody>
</table>

### ReviewStateFilterInput

리뷰 상태 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewstatefilterinput.value">value</strong></td>
<td valign="top"><a href="#reviewstateenum">ReviewStateEnum</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewstatefilterinput.values">values</strong></td>
<td valign="top">[<a href="#reviewstateenum">ReviewStateEnum</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewstatefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### ReviewUpdateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.id">id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.state">state</strong></td>
<td valign="top"><a href="#reviewstateenum">ReviewStateEnum</a></td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.score">score</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.context">context</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

리뷰 내용

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.isvisible">isVisible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

리뷰가 보이는지 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewupdateinputforadmin.writtenat">writtenAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

작성일자

</td>
</tr>
</tbody>
</table>

### ReviewWriteInput

리뷰 작성

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="reviewwriteinput.score">score</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

리뷰 점수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="reviewwriteinput.context">context</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

리뷰 내용

</td>
</tr>
</tbody>
</table>

### ServiceManageUpdateInput

서비스 운영정보 Update Input

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.representativename">representativeName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.mailordersalesregistrationnumber">mailOrderSalesRegistrationNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

통신판매업신고번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.businesslicense">businessLicense</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자등록번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.companyaddress">companyAddress</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.serviceterms">serviceTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

서비스이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.refundterms">refundTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환불규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.marketingterms">marketingTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

마켓팅규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.personalprocessingpolicy">personalProcessingPolicy</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

개인정보처리방침

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.withdrawalterms">withdrawalTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

탈퇴약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.exchangeterms">exchangeTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

환급규정

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.kakaochannel">kakaoChannel</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

카카오 채널

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.thirdpartyconsent">thirdPartyConsent</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

제 3자 정보제공 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.paidserviceterms">paidServiceTerms</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

유료서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.locationinfoterm">locationInfoTerm</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

위치기반 서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="servicemanageupdateinput.kakaotalknotificationconsent">kakaotalkNotificationConsent</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

카카오톡 광고 알림 수신 동의

</td>
</tr>
</tbody>
</table>

### SignUpInput

회원가입 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.realname">realname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

실명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.nickname">nickname</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

닉네임

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.zipcode">zipCode</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 우편번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 상세주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="signupinput.password">password</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

비밀번호

</td>
</tr>
</tbody>
</table>

### SocialSignUpInput

회원가입 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.zipcode">zipCode</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 우편번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

본점 상세주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.ismarketingnoti">isMarketingNoti</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

마케팅 수신여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.isallowgeolocation">isAllowGeolocation</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

위치기반서비스 이용약관

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.isallowthirdparty">isAllowThirdParty</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

제3자 정보제공 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="socialsignupinput.isallowkakaotalk">isAllowKakaotalk</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

카카오톡 알림 수신 동의

</td>
</tr>
</tbody>
</table>

### SortInput

정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="sortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="sortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
</tbody>
</table>

### StringFilterInput

문자열(String) 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="stringfilterinput.value">value</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="stringfilterinput.values">values</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="stringfilterinput.operator">operator</strong></td>
<td valign="top"><a href="#stringfilteroperators">StringFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### StringSortInput

문자열 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="stringsortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="stringsortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="stringsortinput.case">case</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### UserAllowInput

동의항목

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userallowinput.geolocation">geolocation</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

위치기반서비스 이용약관 동의

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userallowinput.thirdparty">thirdParty</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

제3자 정보제공 동의

</td>
</tr>
</tbody>
</table>

### UserFCMTokenAddInput

사용자 FCM 토큰 추가

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtokenaddinput.fcmregistrationtoken">fcmRegistrationToken</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

FCM 등록 토큰

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfcmtokenaddinput.os">os</strong></td>
<td valign="top"><a href="#fcmtokenosenum">FcmTokenOsEnum</a>!</td>
<td>

OS

</td>
</tr>
</tbody>
</table>

### UserFilterInput

사용자 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.idx">idx</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.role">role</strong></td>
<td valign="top">[<a href="#usertypefilterinput">UserTypeFilterInput</a>!]</td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.email">email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.phonenumber">phoneNumber</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.joinedat">joinedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.leavedat">leavedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

탈퇴 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.avatar__id">avatar__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinput.address">address</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소

</td>
</tr>
</tbody>
</table>

### UserFilterInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.id">id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.idx">idx</strong></td>
<td valign="top">[<a href="#intfilterinput">IntFilterInput</a>!]</td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.role">role</strong></td>
<td valign="top">[<a href="#usertypefilterinput">UserTypeFilterInput</a>!]</td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.name">name</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.email">email</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.phonenumber">phoneNumber</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.joinedat">joinedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.leavedat">leavedAt</strong></td>
<td valign="top">[<a href="#datetimefilterinput">DateTimeFilterInput</a>!]</td>
<td>

탈퇴 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.avatar__id">avatar__id</strong></td>
<td valign="top">[<a href="#idfilterinput">IDFilterInput</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.address">address</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.profile__mainbusiness">profile__mainBusiness</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

주력사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userfilterinputforadmin.profile__uniqueid">profile__uniqueId</strong></td>
<td valign="top">[<a href="#stringfilterinput">StringFilterInput</a>!]</td>
<td>

고유번호

</td>
</tr>
</tbody>
</table>

### UserNotificationSettingUpdateInput

사용자 알림 설정 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.marketing">marketing</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

마케팅 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.keyword">keyword</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

키워드 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.notice">notice</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

공지사항 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.chat">chat</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

채팅 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.follow">follow</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

팔로우 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.communitypost">communityPost</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

커뮤니티 게시글 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.communitycommend">communityCommend</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

커뮤니티 댓글 알림

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.locationrange">locationRange</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내 지역 범위로 받기

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usernotificationsettingupdateinput.categoryrange">categoryRange</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내 업종으로 받기

</td>
</tr>
</tbody>
</table>

### UserOrderInput

사용자 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.id">id</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.idx">idx</strong></td>
<td valign="top"><a href="#intsortinput">IntSortInput</a></td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.role">role</strong></td>
<td valign="top"><a href="#usertypesortinput">UserTypeSortInput</a></td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.name">name</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.email">email</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#stringsortinput">StringSortInput</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.joinedat">joinedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userorderinput.leavedat">leavedAt</strong></td>
<td valign="top"><a href="#sortinput">SortInput</a></td>
<td>

탈퇴 날짜/시간

</td>
</tr>
</tbody>
</table>

### UserProfileCompanyTypeUpdateInput

법인/개인 프로필 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.companycode">companyCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

사업자 번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.companytype">companyType</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업태업종

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.licenseids">licenseIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

면허 id

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.mainbusiness">mainBusiness</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력 사업

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.phones">phones</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.addresses">addresses</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.settleaccountday">settleAccountDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

결산일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.stockholders">stockholders</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

주요 주주들

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

기업 로고 사진

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.mainbusinessmenuimgids">mainBusinessMenuImgIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력업종 단가표

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.requestid">requestId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

대표자 휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.managername">managerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 정보

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.managerphonenumber">managerPhoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.managerrequestid">managerRequestId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

담당자 휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofilecompanytypeupdateinput.manageremail">managerEmail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

담당자 이메일

</td>
</tr>
</tbody>
</table>

### UserProfileConsumerTypeUpdateInput

일반 소비자 프로필 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.requestid">requestId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileconsumertypeupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

기업 로고 사진

</td>
</tr>
</tbody>
</table>

### UserProfileEngineerTypeUpdateInput

기술자 프로필 수정

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.companyname">companyName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

상호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.maincategoryids">mainCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(중분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.mainsubcategoryids">mainSubCategoryIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력 업종(소분류)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.phones">phones</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.performancetype">performanceType</strong></td>
<td valign="top"><a href="#profileperformancetypeenum">ProfilePerformanceTypeEnum</a></td>
<td>

업체 실적 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.addresses">addresses</strong></td>
<td valign="top"><a href="#json">JSON</a></td>
<td>

주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.faxnumber">faxNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

팩스번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.createdday">createdDay</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

설립일자

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.homepageurl">homepageUrl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

홈페이지 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.staffcount">staffCount</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

종업원 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.istaxbillissue">isTaxBillIssue</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

세금계산서 발행 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.isrentledgersubmitpossible">isRentLedgerSubmitPossible</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

노임대장 제출 가능 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.mainbusinessprice">mainBusinessPrice</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

주력업종 단가

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.mainbusinessmenuimgids">mainBusinessMenuImgIds</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td>

주력업종 단가표

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.smslinks">smsLinks</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td>

SNS(블로그) 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.ownername">ownerName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

대표자 이름

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

휴대전화

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.requestid">requestId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

휴대폰 인증 후 발급받은 고유 코드

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.description">description</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

업체 소개글

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileengineertypeupdateinput.logoimgid">logoImgId</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

기업 로고 사진

</td>
</tr>
</tbody>
</table>

### UserProfileUpdateInputForAdmin

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.id">id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td>

기본 키(UUID)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.createdat">createdAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

생성 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.deletedat">deletedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

삭제 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.updatedat">updatedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

수정 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.type">type</strong></td>
<td valign="top"><a href="#profiletypeenum">ProfileTypeEnum</a></td>
<td>

프로필 유형

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.uniqueid">uniqueId</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유아이디, 프로필 완성시 결정됨

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.isnicecertified">isNICECertified</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

나이스 인증 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.progress">progress</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

완성도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.companyinfo">companyInfo</strong></td>
<td valign="top"><a href="#profilecompanyinfoupdateinput">ProfileCompanyInfoUpdateInput</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.engineerinfo">engineerInfo</strong></td>
<td valign="top"><a href="#profileengineerinfoupdateinput">ProfileEngineerInfoUpdateInput</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userprofileupdateinputforadmin.consumerinfo">consumerInfo</strong></td>
<td valign="top"><a href="#profileconsumerinfoupdateinput">ProfileConsumerInfoUpdateInput</a></td>
<td></td>
</tr>
</tbody>
</table>

### UserTypeFilterInput

사용자 타입 필터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="usertypefilterinput.value">value</strong></td>
<td valign="top"><a href="#userrole">UserRole</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usertypefilterinput.values">values</strong></td>
<td valign="top">[<a href="#userrole">UserRole</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usertypefilterinput.operator">operator</strong></td>
<td valign="top"><a href="#enumfilteroperators">EnumFilterOperators</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### UserTypeSortInput

사용자 타입 정렬

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="usertypesortinput.order">order</strong></td>
<td valign="top"><a href="#order">Order</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usertypesortinput.nulls">nulls</strong></td>
<td valign="top"><a href="#nulls">Nulls</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="usertypesortinput.case">case</strong></td>
<td valign="top">[<a href="#userrole">UserRole</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### UserUpdateInput

사용자 수정 데이터

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.realname">realname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

실명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.nickname">nickname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

닉네임

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.zipcode">zipCode</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

본점 우편번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

본점 주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

본점 상세주소

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.notificationsetting">notificationSetting</strong></td>
<td valign="top"><a href="#usernotificationsettingupdateinput">UserNotificationSettingUpdateInput</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.allow">allow</strong></td>
<td valign="top"><a href="#userallowinput">UserAllowInput</a></td>
<td>

동의 항목

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="userupdateinput.password">password</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

비밀번호

</td>
</tr>
</tbody>
</table>

## Enums

### AdminPostAction

관리자 게시글 클릭 액션

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>TEXT</strong></td>
<td>

텍스트 표시

</td>
</tr>
<tr>
<td valign="top"><strong>NONE</strong></td>
<td>

액션 없음

</td>
</tr>
<tr>
<td valign="top"><strong>MOVE_URL</strong></td>
<td>

URL 이동

</td>
</tr>
</tbody>
</table>

### AdminPostState

관리자가 올린 게시물 상태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ACTIVE</strong></td>
<td>

활성화

</td>
</tr>
<tr>
<td valign="top"><strong>INACTIVE</strong></td>
<td>

비활성화

</td>
</tr>
</tbody>
</table>

### AdminPostType

관리자가 올린 게시물 타입

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>NOTICE</strong></td>
<td>

공지사항

</td>
</tr>
<tr>
<td valign="top"><strong>FAQ</strong></td>
<td>

자주 묻는 질문

</td>
</tr>
<tr>
<td valign="top"><strong>BANNER</strong></td>
<td>

배너

</td>
</tr>
<tr>
<td valign="top"><strong>POPUP</strong></td>
<td>

팝업

</td>
</tr>
<tr>
<td valign="top"><strong>EVENT</strong></td>
<td>

이벤트

</td>
</tr>
</tbody>
</table>

### AdvertisementLocationEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>FIRST</strong></td>
<td>

첫번째

</td>
</tr>
<tr>
<td valign="top"><strong>SECOND</strong></td>
<td>

두번째

</td>
</tr>
</tbody>
</table>

### AdvertisementStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ACTIVE</strong></td>
<td>

활성화

</td>
</tr>
<tr>
<td valign="top"><strong>INACTIVE</strong></td>
<td>

비활성화

</td>
</tr>
</tbody>
</table>

### AnnouncementApplyStateEnum

입찰 신청 상태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>APPLY</strong></td>
<td>

신청 상태

</td>
</tr>
<tr>
<td valign="top"><strong>SELECTED</strong></td>
<td>

선정됨

</td>
</tr>
<tr>
<td valign="top"><strong>FAIL</strong></td>
<td>

탈락

</td>
</tr>
<tr>
<td valign="top"><strong>WRITING</strong></td>
<td>

작성중

</td>
</tr>
</tbody>
</table>

### AnnouncementAttendanceStateEnum

참여 상태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>APPLIABLE</strong></td>
<td>

참여 가능

</td>
</tr>
<tr>
<td valign="top"><strong>APPLIED</strong></td>
<td>

참여중

</td>
</tr>
<tr>
<td valign="top"><strong>CHOOSING</strong></td>
<td>

업체 선정 중

</td>
</tr>
<tr>
<td valign="top"><strong>END</strong></td>
<td>

종료

</td>
</tr>
<tr>
<td valign="top"><strong>POSTING</strong></td>
<td>

게시중

</td>
</tr>
</tbody>
</table>

### AnnouncementFieldInfo

현장 정보

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>RESIDENCE</strong></td>
<td>

주거

</td>
</tr>
<tr>
<td valign="top"><strong>MERCANTILE</strong></td>
<td>

상업

</td>
</tr>
<tr>
<td valign="top"><strong>INDUSTRY</strong></td>
<td>

공업

</td>
</tr>
<tr>
<td valign="top"><strong>CULTURE</strong></td>
<td>

문화

</td>
</tr>
<tr>
<td valign="top"><strong>MEDICAL</strong></td>
<td>

의료

</td>
</tr>
<tr>
<td valign="top"><strong>EDUCATION</strong></td>
<td>

교육

</td>
</tr>
<tr>
<td valign="top"><strong>RECREATION</strong></td>
<td>

휴양

</td>
</tr>
<tr>
<td valign="top"><strong>TERMINATION</strong></td>
<td>

종교

</td>
</tr>
<tr>
<td valign="top"><strong>ETC</strong></td>
<td>

기타

</td>
</tr>
</tbody>
</table>

### AnnouncementOrderType

발주형태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PUBLIC</strong></td>
<td>

공공 발주

</td>
</tr>
<tr>
<td valign="top"><strong>PRIVATE</strong></td>
<td>

민간 발주

</td>
</tr>
</tbody>
</table>

### AnnouncementStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PROCESSING</strong></td>
<td>

참여가능(진행중)

</td>
</tr>
<tr>
<td valign="top"><strong>CHOOSING</strong></td>
<td>

업체선정중

</td>
</tr>
<tr>
<td valign="top"><strong>SELECTED</strong></td>
<td>

선정됨

</td>
</tr>
<tr>
<td valign="top"><strong>UNSELECTED</strong></td>
<td>

선정되지 않음

</td>
</tr>
</tbody>
</table>

### AnnouncementWorkScopeEnum

공사 범위

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ALL</strong></td>
<td>

전체

</td>
</tr>
<tr>
<td valign="top"><strong>INTERNAL</strong></td>
<td>

내부

</td>
</tr>
<tr>
<td valign="top"><strong>OUTSIDE</strong></td>
<td>

외부

</td>
</tr>
<tr>
<td valign="top"><strong>ETC</strong></td>
<td>

기타

</td>
</tr>
</tbody>
</table>

### AnnouncementWorkType

공사 유형

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>NEW_WORK</strong></td>
<td>

신축공사

</td>
</tr>
<tr>
<td valign="top"><strong>REPAIR</strong></td>
<td>

리모델링(수리)

</td>
</tr>
<tr>
<td valign="top"><strong>ETC</strong></td>
<td>

기타

</td>
</tr>
</tbody>
</table>

### BooleanFilterOperators

논리 필터 연산자

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NULL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NOT_NULL</strong></td>
<td></td>
</tr>
</tbody>
</table>

### CRIPriorityEnum

cri 순서

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>D</strong></td>
<td>

D

</td>
</tr>
<tr>
<td valign="top"><strong>C</strong></td>
<td>

C

</td>
</tr>
<tr>
<td valign="top"><strong>CC</strong></td>
<td>

CC

</td>
</tr>
<tr>
<td valign="top"><strong>CCC_MINUS</strong></td>
<td>

CCC-

</td>
</tr>
<tr>
<td valign="top"><strong>CCC</strong></td>
<td>

CCC

</td>
</tr>
<tr>
<td valign="top"><strong>CCC_PLUS</strong></td>
<td>

CCC+

</td>
</tr>
<tr>
<td valign="top"><strong>B_MINUS</strong></td>
<td>

B-

</td>
</tr>
<tr>
<td valign="top"><strong>B</strong></td>
<td>

B

</td>
</tr>
<tr>
<td valign="top"><strong>B_PLUS</strong></td>
<td>

B+

</td>
</tr>
<tr>
<td valign="top"><strong>BB_MINUS</strong></td>
<td>

BB-

</td>
</tr>
<tr>
<td valign="top"><strong>BB</strong></td>
<td>

BB

</td>
</tr>
<tr>
<td valign="top"><strong>BB_PLUS</strong></td>
<td>

BB+

</td>
</tr>
<tr>
<td valign="top"><strong>BBB_MINUS</strong></td>
<td>

BBB-

</td>
</tr>
<tr>
<td valign="top"><strong>BBB</strong></td>
<td>

BBB

</td>
</tr>
<tr>
<td valign="top"><strong>BBB_PLUS</strong></td>
<td>

BBB+

</td>
</tr>
<tr>
<td valign="top"><strong>A_MINUS</strong></td>
<td>

A-

</td>
</tr>
<tr>
<td valign="top"><strong>A</strong></td>
<td>

A

</td>
</tr>
<tr>
<td valign="top"><strong>A_PLUS</strong></td>
<td>

A+

</td>
</tr>
<tr>
<td valign="top"><strong>AA_MINUS</strong></td>
<td>

AA-

</td>
</tr>
<tr>
<td valign="top"><strong>AA</strong></td>
<td>

AA

</td>
</tr>
<tr>
<td valign="top"><strong>AA_PLUS</strong></td>
<td>

AA+

</td>
</tr>
<tr>
<td valign="top"><strong>AAA</strong></td>
<td>

AAA

</td>
</tr>
</tbody>
</table>

### CategoryTypeEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>DEPTH_1</strong></td>
<td>

1뎁스

</td>
</tr>
<tr>
<td valign="top"><strong>DEPTH_2</strong></td>
<td>

2뎁스

</td>
</tr>
<tr>
<td valign="top"><strong>DEPTH_3</strong></td>
<td>

3뎁스

</td>
</tr>
</tbody>
</table>

### CommunityReportCategoryEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ABUSIVE</strong></td>
<td>

욕설

</td>
</tr>
<tr>
<td valign="top"><strong>SENSUALITY</strong></td>
<td>

선정성

</td>
</tr>
<tr>
<td valign="top"><strong>ETC</strong></td>
<td>

기타

</td>
</tr>
</tbody>
</table>

### CommunityReportStateEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PENDING</strong></td>
<td>

대기중

</td>
</tr>
<tr>
<td valign="top"><strong>PROCESSING</strong></td>
<td>

처리중

</td>
</tr>
<tr>
<td valign="top"><strong>COMPLETE</strong></td>
<td>

완료

</td>
</tr>
</tbody>
</table>

### CommunityReportType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>POST</strong></td>
<td>

게시글

</td>
</tr>
<tr>
<td valign="top"><strong>REPLY</strong></td>
<td>

댓글

</td>
</tr>
</tbody>
</table>

### EnumFilterOperators

Enum 필터 연산자

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NULL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NOT_NULL</strong></td>
<td></td>
</tr>
</tbody>
</table>

### FcmTokenOsEnum

Fcm토큰 OS

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ANDROID</strong></td>
<td>

AOS

</td>
</tr>
<tr>
<td valign="top"><strong>IOS</strong></td>
<td>

iOS

</td>
</tr>
<tr>
<td valign="top"><strong>WEB</strong></td>
<td>

web

</td>
</tr>
</tbody>
</table>

### IDFilterOperators

ID 필터 연산자

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NULL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NOT_NULL</strong></td>
<td></td>
</tr>
</tbody>
</table>

### InquireState

문의 상태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ACTIVE</strong></td>
<td>

답변 대기중

</td>
</tr>
<tr>
<td valign="top"><strong>CHECKING</strong></td>
<td>

확인중 / 진행중

</td>
</tr>
<tr>
<td valign="top"><strong>ANSWERED</strong></td>
<td>

답변 완료

</td>
</tr>
</tbody>
</table>

### InquireType

문의 종류

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>COMMON</strong></td>
<td>

일반

</td>
</tr>
</tbody>
</table>

### MatchPostStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>IN_PROGRESS</strong></td>
<td>

진행중

</td>
</tr>
<tr>
<td valign="top"><strong>IN_RESERVATION</strong></td>
<td>

예약중

</td>
</tr>
<tr>
<td valign="top"><strong>DEAL_DONE</strong></td>
<td>

거래완료

</td>
</tr>
</tbody>
</table>

### MyAnnouncementTabEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>APPLIED</strong></td>
<td>

참여중

</td>
</tr>
<tr>
<td valign="top"><strong>POSTING</strong></td>
<td>

게시중

</td>
</tr>
</tbody>
</table>

### NotificationStorageTargetType

알림 타겟

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ALL</strong></td>
<td>

전체

</td>
</tr>
<tr>
<td valign="top"><strong>SPECIFIC</strong></td>
<td>

특정인원

</td>
</tr>
<tr>
<td valign="top"><strong>ANDROID</strong></td>
<td>

안드 유저만

</td>
</tr>
<tr>
<td valign="top"><strong>iOS</strong></td>
<td>

iOS유저만

</td>
</tr>
</tbody>
</table>

### NotificationType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>NOTICE</strong></td>
<td>

공지사항 알림

</td>
</tr>
<tr>
<td valign="top"><strong>MARKETING</strong></td>
<td>

마케팅 알림 (이벤트, 광고 등)

</td>
</tr>
<tr>
<td valign="top"><strong>KEYWORD</strong></td>
<td>

키워드 알림

</td>
</tr>
<tr>
<td valign="top"><strong>FOLLOW</strong></td>
<td>

팔로우 알림

</td>
</tr>
<tr>
<td valign="top"><strong>CHAT</strong></td>
<td>

채팅 알림

</td>
</tr>
<tr>
<td valign="top"><strong>INQUIRE</strong></td>
<td>

문의 관련 알림

</td>
</tr>
<tr>
<td valign="top"><strong>COMMUNITY_POST</strong></td>
<td>

커뮤니티 게시글 알림

</td>
</tr>
<tr>
<td valign="top"><strong>COMMUNITY_COMMEND</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>MATCH_POST</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Nulls

정렬 시 null 순서

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>FIRST</strong></td>
<td>

null 먼저

</td>
</tr>
<tr>
<td valign="top"><strong>LAST</strong></td>
<td>

null 마지막에

</td>
</tr>
</tbody>
</table>

### NumberFilterOperators

숫자 필터 연산자

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>LESS_THAN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>LESS_THAN_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>GREATER_THAN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>GREATER_THAN_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>BETWEEN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_BETWEEN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NULL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NOT_NULL</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Order

정렬 순서

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ASCENDING</strong></td>
<td>

오름차순

</td>
</tr>
<tr>
<td valign="top"><strong>DESCENDING</strong></td>
<td>

내림차순

</td>
</tr>
</tbody>
</table>

### PaymentItemAuthEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>READ</strong></td>
<td>

열람만

</td>
</tr>
<tr>
<td valign="top"><strong>READ_AND_ISSUE</strong></td>
<td>

열람/발급 가능

</td>
</tr>
</tbody>
</table>

### PaymentItemTypeEnum

구매 항목

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>POINT_CHARGING</strong></td>
<td>

포인트 충전

</td>
</tr>
<tr>
<td valign="top"><strong>REGULAR_PAYMENT</strong></td>
<td>

정기결제

</td>
</tr>
<tr>
<td valign="top"><strong>SINGLE_PAYMENT</strong></td>
<td>

일시불

</td>
</tr>
</tbody>
</table>

### PaymentMethodEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>CARD</strong></td>
<td>

카드

</td>
</tr>
<tr>
<td valign="top"><strong>BANK</strong></td>
<td>

계좌이체

</td>
</tr>
<tr>
<td valign="top"><strong>VBANK</strong></td>
<td>

가상계좌

</td>
</tr>
<tr>
<td valign="top"><strong>CELLPHONE</strong></td>
<td>

휴대폰

</td>
</tr>
</tbody>
</table>

### PaymentRefundStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>SUCCESS</strong></td>
<td>

성공

</td>
</tr>
<tr>
<td valign="top"><strong>FAILED</strong></td>
<td>

실패

</td>
</tr>
<tr>
<td valign="top"><strong>PENDING</strong></td>
<td>

대기중

</td>
</tr>
</tbody>
</table>

### PaymentStateEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PENDING</strong></td>
<td>

대기중

</td>
</tr>
<tr>
<td valign="top"><strong>SUCCESS</strong></td>
<td>

성공

</td>
</tr>
<tr>
<td valign="top"><strong>FAILED</strong></td>
<td>

실패

</td>
</tr>
<tr>
<td valign="top"><strong>REFUND</strong></td>
<td>

환불

</td>
</tr>
</tbody>
</table>

### PointRefundStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>APPLY</strong></td>
<td>

신청

</td>
</tr>
<tr>
<td valign="top"><strong>ALLOW</strong></td>
<td>

수락

</td>
</tr>
<tr>
<td valign="top"><strong>REJECT</strong></td>
<td>

거부

</td>
</tr>
</tbody>
</table>

### PointTypeEnum

포인트 발생 구분

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ADMIN</strong></td>
<td>

관리자 부여

</td>
</tr>
<tr>
<td valign="top"><strong>COMPANY_INFORMATION</strong></td>
<td>

기업 정보 열람

</td>
</tr>
<tr>
<td valign="top"><strong>COMPANY_REPORT</strong></td>
<td>

총괄 기업 보고서 열람 + 발급

</td>
</tr>
<tr>
<td valign="top"><strong>BID</strong></td>
<td>

입찰 참여

</td>
</tr>
<tr>
<td valign="top"><strong>PURCHASE</strong></td>
<td>

포인트 구매

</td>
</tr>
<tr>
<td valign="top"><strong>REFUND</strong></td>
<td>

환불

</td>
</tr>
<tr>
<td valign="top"><strong>ETC</strong></td>
<td>

기타

</td>
</tr>
<tr>
<td valign="top"><strong>EMERGENCY_ANNOUNCEMENT</strong></td>
<td>

긴급 공사

</td>
</tr>
</tbody>
</table>

### PortfolioConstructionTypeEnum

공사 구분

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PUBLIC</strong></td>
<td>

공공 공사

</td>
</tr>
<tr>
<td valign="top"><strong>PRIVATE_SECTOR</strong></td>
<td>

민간공사

</td>
</tr>
</tbody>
</table>

### PortfolioRecommendationStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>ACTIVE</strong></td>
<td>

활성화

</td>
</tr>
<tr>
<td valign="top"><strong>INACTIVE</strong></td>
<td>

비활성화

</td>
</tr>
</tbody>
</table>

### PortfolioServicePriceTypeEnum

서비스 금액 타입

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>LESSTHEN_500</strong></td>
<td>

500만원 이하

</td>
</tr>
<tr>
<td valign="top"><strong>OVER_500_LESSTHEN_1000</strong></td>
<td>

500~1000

</td>
</tr>
<tr>
<td valign="top"><strong>OVER_1000_LESSTHEN_3000</strong></td>
<td>

1000~3000

</td>
</tr>
<tr>
<td valign="top"><strong>OVER_3000_LESSTHEN_5000</strong></td>
<td>

3000~5000

</td>
</tr>
<tr>
<td valign="top"><strong>OVER_5000_LESSTHEN_10000</strong></td>
<td>

5000~10000

</td>
</tr>
<tr>
<td valign="top"><strong>OVER_10000</strong></td>
<td>

10000

</td>
</tr>
</tbody>
</table>

### ProfilePerformanceTypeEnum

프로필 법인/개인 업체 실적

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PORTFOLIO</strong></td>
<td>

3년간 공사대장 통보실적 가져오기 KISCON,외부데이터

</td>
</tr>
<tr>
<td valign="top"><strong>KISCON</strong></td>
<td>

자체 제보 누적실적 가져오기 * 출처 : 모두의 건축 포트폴리오

</td>
</tr>
</tbody>
</table>

### ProfileTypeEnum

프로필 유형

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>CORPORATION</strong></td>
<td>

법인/기업

</td>
</tr>
<tr>
<td valign="top"><strong>PRIVATE_BUSINESS</strong></td>
<td>

개인 사업자

</td>
</tr>
<tr>
<td valign="top"><strong>ENGINEER</strong></td>
<td>

기술자

</td>
</tr>
<tr>
<td valign="top"><strong>CONSUMER</strong></td>
<td>

일반 소비자

</td>
</tr>
</tbody>
</table>

### ReportCategoryEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>USER</strong></td>
<td>

사용자 신고

</td>
</tr>
</tbody>
</table>

### ReportStateEnumType

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PENDING</strong></td>
<td>

대기중

</td>
</tr>
<tr>
<td valign="top"><strong>PROCESSING</strong></td>
<td>

처리중

</td>
</tr>
<tr>
<td valign="top"><strong>COMPLETE</strong></td>
<td>

완료

</td>
</tr>
</tbody>
</table>

### ReviewStateEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>WRITING</strong></td>
<td>

작성중/작성필요

</td>
</tr>
<tr>
<td valign="top"><strong>DONE</strong></td>
<td>

작성완료

</td>
</tr>
</tbody>
</table>

### SigunguTypeEnum

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>SI</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>GUNGU</strong></td>
<td></td>
</tr>
</tbody>
</table>

### StringFilterOperators

문자열 필터 연산자

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_EQUAL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>LIKE</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_LIKE</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>ILIKE</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_ILIKE</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>NOT_IN</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NULL</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>IS_NOT_NULL</strong></td>
<td></td>
</tr>
</tbody>
</table>

### UserRole

사용자 권한

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>MEMBER</strong></td>
<td>

일반 사용자

</td>
</tr>
<tr>
<td valign="top"><strong>ADMIN</strong></td>
<td>

관리자

</td>
</tr>
</tbody>
</table>

### UserSocialType

사용자 소셜 종류

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>KAKAO</strong></td>
<td>

카카오

</td>
</tr>
<tr>
<td valign="top"><strong>APPLE</strong></td>
<td>

애플

</td>
</tr>
<tr>
<td valign="top"><strong>NAVER</strong></td>
<td>

네이버

</td>
</tr>
<tr>
<td valign="top"><strong>GOOGLE</strong></td>
<td>

구글

</td>
</tr>
</tbody>
</table>

### UserState

사용자 상태

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>PENDING</strong></td>
<td>

가입 대기중

</td>
</tr>
<tr>
<td valign="top"><strong>ACTIVE</strong></td>
<td>

활성화 상태

</td>
</tr>
<tr>
<td valign="top"><strong>INACTIVE</strong></td>
<td>

비활성화 상태 - 휴면계정

</td>
</tr>
<tr>
<td valign="top"><strong>SUSPENDED</strong></td>
<td>

정지

</td>
</tr>
<tr>
<td valign="top"><strong>LEAVED</strong></td>
<td>

탈퇴상태

</td>
</tr>
</tbody>
</table>

## Scalars

### Boolean

The `Boolean` scalar type represents `true` or `false`.

### DateTime

A date-time string at UTC, such as 2019-12-03T09:54:33Z, compliant with the date-time format.

### Email

이메일 (xxxxx@xxxxx.xxx)

### Float

The `Float` scalar type represents signed double-precision fractional values as specified by [IEEE 754](https://en.wikipedia.org/wiki/IEEE_floating_point).

### ID

The `ID` scalar type represents a unique identifier, often used to refetch an object or as key for a cache. The ID type appears in a JSON response as a String; however, it is not intended to be human-readable. When expected as an input type, any string (such as `"4"`) or integer (such as `4`) input value will be accepted as an ID.

### Int

The `Int` scalar type represents non-fractional signed whole numeric values. Int can represent values between -(2^31) and 2^31 - 1.

### JSON

JSON

### PhoneNumber

전화번호 (000-0000-0000)

### String

The `String` scalar type represents textual data, represented as UTF-8 character sequences. The String type is most often used by GraphQL to represent free-form human-readable text.


## Interfaces


### AdminPost

관리자가 올린 게시물

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="adminpost.type">type</strong></td>
<td valign="top"><a href="#adminposttype">AdminPostType</a>!</td>
<td>

타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpost.state">state</strong></td>
<td valign="top"><a href="#adminpoststate">AdminPostState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="adminpost.category">category</strong></td>
<td valign="top"><a href="#adminpostcategory">AdminPostCategory</a></td>
<td>

카테고리

</td>
</tr>
</tbody>
</table>

**Possible Types:** [Notice](#notice), [Faq](#faq), [Banner](#banner), [Popup](#popup), [Event](#event)

### User

사용자

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="user.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td>

UUID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.idx">idx</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

고유번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.role">role</strong></td>
<td valign="top"><a href="#userrole">UserRole</a>!</td>
<td>

권한 타입

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.state">state</strong></td>
<td valign="top"><a href="#userstate">UserState</a>!</td>
<td>

상태

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

고유 이름(아이디)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.realname">realname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

실명

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.nickname">nickname</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

닉네임

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.email">email</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.phonenumber">phoneNumber</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

전화번호

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.joinedat">joinedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a>!</td>
<td>

가입 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.leavedat">leavedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

탈퇴 날짜/시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.suspendedat">suspendedAt</strong></td>
<td valign="top"><a href="#datetime">DateTime</a></td>
<td>

정지 처리된 시간

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.address">address</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.addressdetail">addressDetail</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.latitude">latitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

위도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.longitude">longitude</strong></td>
<td valign="top"><a href="#float">Float</a></td>
<td>

경도

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.isfollowing">isFollowing</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td>

내가 해당 사용자를 팔로잉한 여부

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.avatar">avatar</strong></td>
<td valign="top"><a href="#file">File</a></td>
<td>

프로필 이미지(아바타)

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.socialtype">socialType</strong></td>
<td valign="top"><a href="#usersocialtype">UserSocialType</a></td>
<td>

가입 방법,null이면 이메일

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.profile">profile</strong></td>
<td valign="top"><a href="#userprofile">UserProfile</a></td>
<td>

유저 프로필

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.favoriteprofilecount">favoriteProfileCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 기업 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.favoriteannouncementcount">favoriteAnnouncementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 공고 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.favoriteportfoliocount">favoritePortfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

내 관심 포트폴리오 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.portfoliocount">portfolioCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포트폴리오 개수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.allow">allow</strong></td>
<td valign="top"><a href="#userallow">UserAllow</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.notificationsetting">notificationSetting</strong></td>
<td valign="top"><a href="#usernotificationsetting">UserNotificationSetting</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.announcementcount">announcementCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 작성 수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.announcementapplycount">announcementApplyCount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

공고 참여 횟수

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.point">point</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

보유 포인트

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.pointchargeamount">pointChargeAmount</strong></td>
<td valign="top"><a href="#float">Float</a>!</td>
<td>

포인트 충전 금액

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.adminmemo">adminMemo</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td>

관리자용 유저 메모

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.ismine">isMine</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

나 인지

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="user.socials">socials</strong></td>
<td valign="top">[<a href="#usersociallink">UserSocialLink</a>]!</td>
<td>

소셜 서비스 연결 리스트

</td>
</tr>
</tbody>
</table>

**Possible Types:** [Member](#member), [Admin](#admin)

## Unions

### CommunityReportTarget

<table>
<thead>
<tr>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong><a href="#communitypost">CommunityPost</a></strong></td>
<td valign="top">

커뮤니티 게시물

</td>
</tr>
<tr>
<td valign="top"><strong><a href="#communitypostreply">CommunityPostReply</a></strong></td>
<td valign="top">

커뮤니티 게시물 댓글

</td>
</tr>
</tbody>
</table>

### ProfileInfo

<table>
<thead>
<tr>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong><a href="#profilecompanyinfo">ProfileCompanyInfo</a></strong></td>
<td valign="top">

프로필 법인 정보

</td>
</tr>
<tr>
<td valign="top"><strong><a href="#profileconsumerinfo">ProfileConsumerInfo</a></strong></td>
<td valign="top">

프로필 일반 소비자 정보

</td>
</tr>
<tr>
<td valign="top"><strong><a href="#profileengineerinfo">ProfileEngineerInfo</a></strong></td>
<td valign="top">

프로필 기술자 정보

</td>
</tr>
</tbody>
</table>
