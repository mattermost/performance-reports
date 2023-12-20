### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 462ms | 461ms | 54366.48
| TeamStore.AnalyticsTeamCount | avg | 1ms | 4ms | 3ms | 232.74
| StatusStore.SaveOrUpdate | avg | 34ms | 60ms | 26ms | 76.84
| ChannelStore.GetTeamChannels | avg | 17ms | 24ms | 7ms | 42.40
| PostStore.SearchPostsForUser | avg | 153ms | 168ms | 15ms | 9.83
| UserStore.GetProfilesInChannel | avg | 176ms | 185ms | 9ms | 5.12
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 498ms | 493ms | 9950.62
| ChannelStore.GetTeamChannels | p99 | 25ms | 96ms | 71ms | 285.65
| ChannelStore.GetChannelUnread | p99 | 5ms | 19ms | 14ms | 282.83
| JobStore.UpdateStatus | p99 | 5ms | 18ms | 13ms | 262.63
| UserStore.Update | p99 | 24ms | 69ms | 45ms | 185.61
| UserAccessTokenStore.GetByToken | p99 | 8ms | 22ms | 14ms | 179.76
| PostStore.GetPostsAfter | p99 | 8ms | 19ms | 11ms | 131.73
| ChannelStore.GetMember | p99 | 10ms | 22ms | 12ms | 123.11
| ChannelStore.Save | p99 | 32ms | 66ms | 34ms | 104.62
| PostStore.Delete | p99 | 25ms | 47ms | 22ms | 89.61
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.78
| JobStore.Save | p99 | 5ms | 8ms | 3ms | 60.61
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 8ms | 3ms | 60.61
| StatusStore.SaveOrUpdate | p99 | 497ms | 741ms | 244ms | 49.11
| JobStore.GetCountByStatusAndType | p99 | 13ms | 18ms | 5ms | 37.17
| ChannelStore.GetAllChannelMembersForUser | p99 | 10ms | 13ms | 3ms | 29.48
| JobStore.GetAllByStatus | p99 | 32ms | 37ms | 5ms | 15.60
| StatusStore.GetByIds | p99 | 18ms | 20ms | 2ms | 10.88
| UserStore.AutocompleteUsersInChannel | p99 | 288ms | 316ms | 28ms | 9.73
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -114.65
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -112.09
| ComplianceStore.MessageExport | avg | 3ms | 0s | -3ms | -104.08
| ChannelStore.AnalyticsTypeCount | avg | 11ms | 0s | -11ms | -101.75
| ChannelStore.CreateSidebarCategory | avg | 30ms | 0s | -30ms | -100.83
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 78ms | 0s | -78ms | -100.12
| ChannelStore.GetMembers | avg | 113ms | 0s | -113ms | -99.85
| UserStore.AnalyticsActiveCount | avg | 25ms | 0s | -25ms | -99.30
| ChannelStore.GetMembersForUserWithPagination | avg | 16ms | 0s | -16ms | -99.23
| ProductNoticesStore.GetViews | avg | 6ms | 0s | -6ms | -97.65
| FileInfoStore.Search | avg | 3ms | 0s | -3ms | -97.12
| EmojiStore.GetMultipleByName | avg | 4ms | 0s | -4ms | -92.17
| DraftStore.Delete | avg | 2ms | 0s | -2ms | -91.08
| PluginStore.List | avg | 11ms | 1ms | -10ms | -90.00
| DraftStore.Upsert | avg | 2ms | 0s | -2ms | -85.26
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -85.22
| StatusStore.UpdateExpiredDNDStatuses | avg | 3ms | 1ms | -2ms | -72.28
| ChannelStore.AutocompleteInTeamForSearch | avg | 34ms | 20ms | -14ms | -41.05
| PostStore.GetPostReminders | avg | 5ms | 3ms | -2ms | -40.05
| ChannelStore.UpdateSidebarCategories | avg | 49ms | 30ms | -19ms | -39.08
| ChannelStore.CreateDirectChannel | avg | 16ms | 13ms | -3ms | -19.11
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 17ms | 15ms | -2ms | -12.10
| ChannelStore.CreateInitialSidebarCategories | avg | 17ms | 15ms | -2ms | -12.09
| ProductNoticesStore.View | avg | 30ms | 27ms | -3ms | -9.84
| TeamStore.SaveMember | avg | 27ms | 25ms | -2ms | -7.51
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 27ms | 25ms | -2ms | -7.41
| ChannelStore.SaveMember | avg | 29ms | 27ms | -2ms | -6.80
| UserStore.GetAllProfilesInChannel | avg | 274ms | 257ms | -17ms | -6.21
| UserStore.Save | avg | 73ms | 70ms | -3ms | -4.12
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 10ms | 0s | -10ms | -103.28
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.GetDraftsForUser | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.AnalyticsTypeCount | p99 | 25ms | 0s | -25ms | -100.93
| DraftStore.Get | p99 | 5ms | 0s | -5ms | -100.93
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.90
| FileInfoStore.Search | p99 | 5ms | 0s | -5ms | -100.89
| ProductNoticesStore.GetViews | p99 | 10ms | 0s | -10ms | -100.50
| ChannelStore.GetMembers | p99 | 466ms | 0s | -466ms | -100.08
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 212ms | 0s | -212ms | -100.04
| EmojiStore.GetMultipleByName | p99 | 47ms | 0s | -47ms | -100.00
| ChannelStore.CreateSidebarCategory | p99 | 98ms | 0s | -98ms | -99.93
| ChannelStore.GetMembersForUserWithPagination | p99 | 49ms | 0s | -49ms | -99.61
| UserStore.AnalyticsActiveCount | p99 | 49ms | 0s | -49ms | -99.24
| JobStore.GetAllByTypePage | p99 | 22ms | 0s | -22ms | -98.66
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 5ms | -41ms | -89.62
| PostStore.GetPostReminders | p99 | 46ms | 5ms | -41ms | -89.62
| ChannelStore.UpdateSidebarCategories | p99 | 438ms | 50ms | -388ms | -88.68
| PluginStore.List | p99 | 51ms | 8ms | -43ms | -84.31
| PostPriorityStore.GetForPost | p99 | 50ms | 9ms | -41ms | -81.60
| JobStore.UpdateOptimistically | p99 | 16ms | 5ms | -11ms | -70.88
| ChannelStore.GetSidebarCategory | p99 | 79ms | 25ms | -54ms | -68.36
| ChannelStore.GetChannelsByUser | p99 | 25ms | 9ms | -16ms | -65.07
| RoleStore.ChannelHigherScopedPermissions | p99 | 21ms | 8ms | -13ms | -63.24
| ChannelStore.AutocompleteInTeamForSearch | p99 | 235ms | 89ms | -146ms | -62.26
| ChannelStore.CreateDirectChannel | p99 | 120ms | 48ms | -72ms | -60.24
| JobStore.Get | p99 | 43ms | 18ms | -25ms | -58.14
| UserStore.GetMany | p99 | 22ms | 9ms | -13ms | -57.87
| LinkMetadataStore.Save | p99 | 17ms | 9ms | -8ms | -46.11
| PluginStore.SetWithOptions | p99 | 43ms | 24ms | -19ms | -43.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 9ms | 5ms | -4ms | -42.33
| FileInfoStore.SetContent | p99 | 40ms | 23ms | -17ms | -42.06
| ThreadStore.GetTeamsUnreadForUser | p99 | 42ms | 25ms | -17ms | -40.94
| FileInfoStore.AttachToPost | p99 | 35ms | 21ms | -14ms | -39.95
| ClusterDiscoveryStore.SetLastPingAt | p99 | 30ms | 18ms | -12ms | -39.34
| PostPersistentNotificationStore.GetSingle | p99 | 16ms | 10ms | -6ms | -37.69
| PostStore.GetPostReminderMetadata | p99 | 8ms | 5ms | -3ms | -37.62
| TeamStore.GetTeamsForUser | p99 | 38ms | 24ms | -14ms | -37.28
| FileInfoStore.Get | p99 | 16ms | 10ms | -6ms | -36.94
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 16ms | 10ms | -6ms | -36.62
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 8ms | 5ms | -3ms | -36.20
| ChannelStore.CreateInitialSidebarCategories | p99 | 155ms | 99ms | -56ms | -36.04
| UserStore.Get | p99 | 14ms | 9ms | -5ms | -35.93
| PostAcknowledgementStore.GetForPost | p99 | 25ms | 16ms | -9ms | -35.82
| ReactionStore.GetForPost | p99 | 20ms | 13ms | -7ms | -34.43
| FileInfoStore.GetForPost | p99 | 12ms | 8ms | -4ms | -34.16
| ThreadStore.GetThreadForUser | p99 | 38ms | 25ms | -13ms | -33.88
| ReactionStore.Save | p99 | 51ms | 34ms | -17ms | -33.57
| GroupStore.GetByName | p99 | 36ms | 24ms | -12ms | -33.44
| ReactionStore.GetUniqueCountForPost | p99 | 18ms | 12ms | -6ms | -33.39
| WebhookStore.GetOutgoingByTeam | p99 | 42ms | 28ms | -14ms | -33.08
| ThreadStore.MarkAsRead | p99 | 15ms | 10ms | -5ms | -32.55
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 143ms | 98ms | -45ms | -31.54
| ReactionStore.ExistsOnPost | p99 | 23ms | 16ms | -7ms | -31.05
| PreferenceStore.Save | p99 | 83ms | 58ms | -25ms | -30.10
| TeamStore.GetTeamsByUserId | p99 | 33ms | 23ms | -10ms | -29.92
| PostStore.GetPostIdBeforeTime | p99 | 20ms | 14ms | -6ms | -29.58
| PreferenceStore.GetAll | p99 | 37ms | 26ms | -11ms | -29.48
| UserStore.GetForLogin | p99 | 34ms | 24ms | -10ms | -29.34
| UserStore.GetByUsername | p99 | 31ms | 22ms | -9ms | -28.80
| ThreadStore.UpdateMembership | p99 | 14ms | 10ms | -4ms | -28.78
| PostStore.Get | p99 | 35ms | 25ms | -10ms | -28.75
| ThreadStore.MaintainMembership | p99 | 32ms | 23ms | -9ms | -28.21
| UserStore.GetUnreadCount | p99 | 25ms | 18ms | -7ms | -28.03
| ThreadStore.GetMembershipForUser | p99 | 22ms | 16ms | -6ms | -27.64
| AuditStore.Save | p99 | 33ms | 24ms | -9ms | -27.44
| ChannelStore.GetByName | p99 | 40ms | 29ms | -11ms | -27.25
| PostStore.Save | p99 | 66ms | 48ms | -18ms | -27.15
| TeamStore.GetAllPage | p99 | 31ms | 23ms | -8ms | -25.49
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 31ms | 23ms | -8ms | -25.47
| SessionStore.Get | p99 | 63ms | 47ms | -16ms | -25.24
| ChannelStore.SearchGroupChannels | p99 | 32ms | 24ms | -8ms | -24.82
| SessionStore.UpdateLastActivityAt | p99 | 21ms | 16ms | -5ms | -24.30
| PluginStore.Delete | p99 | 21ms | 16ms | -5ms | -23.37
| PostStore.GetPosts | p99 | 31ms | 24ms | -7ms | -22.92
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 22ms | 17ms | -5ms | -22.85
| ChannelStore.SaveMember | p99 | 198ms | 153ms | -45ms | -22.77
| PostAcknowledgementStore.GetForPosts | p99 | 23ms | 18ms | -5ms | -22.13
| PreferenceStore.Get | p99 | 24ms | 19ms | -5ms | -21.07
| UserStore.GetProfileByIds | p99 | 25ms | 20ms | -5ms | -20.14
| PostStore.GetEtag | p99 | 30ms | 24ms | -6ms | -20.06
| ChannelStore.GetGuestCount | p99 | 41ms | 33ms | -8ms | -19.59
| StatusStore.UpdateLastActivityAt | p99 | 21ms | 17ms | -4ms | -19.20
| SystemStore.GetByName | p99 | 26ms | 21ms | -5ms | -19.05
| ChannelStore.GetMembersForUser | p99 | 27ms | 22ms | -5ms | -18.32
| ChannelStore.UpdateLastViewedAt | p99 | 22ms | 18ms | -4ms | -18.13
| UserStore.GetProfilesByUsernames | p99 | 23ms | 19ms | -4ms | -17.08
| SessionStore.Save | p99 | 47ms | 39ms | -8ms | -16.99
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 24ms | 20ms | -4ms | -16.89
| UserStore.UpdateFailedPasswordAttempts | p99 | 36ms | 30ms | -6ms | -16.59
| PostPriorityStore.GetForPosts | p99 | 24ms | 20ms | -4ms | -16.46
| ChannelStore.GetPinnedPostCount | p99 | 25ms | 21ms | -4ms | -16.25
| ThreadStore.GetThreadFollowers | p99 | 20ms | 17ms | -3ms | -15.22
| UserStore.IsEmpty | p99 | 20ms | 17ms | -3ms | -15.07
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 27ms | 23ms | -4ms | -14.80
| TeamStore.Get | p99 | 14ms | 12ms | -2ms | -14.72
| ThreadStore.GetTotalUnreadThreads | p99 | 27ms | 23ms | -4ms | -14.72
| ThreadStore.GetTotalUnreadMentions | p99 | 28ms | 24ms | -4ms | -14.18
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 24ms | 21ms | -3ms | -12.74
| ChannelStore.Get | p99 | 24ms | 21ms | -3ms | -12.47
| ChannelStore.IncrementMentionCount | p99 | 24ms | 21ms | -3ms | -12.40
| ChannelStore.GetChannels | p99 | 24ms | 21ms | -3ms | -12.36
| FileInfoStore.Save | p99 | 25ms | 22ms | -3ms | -12.04
| PostStore.GetPostsBefore | p99 | 25ms | 22ms | -3ms | -11.92
| UserTermsOfServiceStore.GetByUser | p99 | 25ms | 22ms | -3ms | -11.85
| StatusStore.Get | p99 | 26ms | 23ms | -3ms | -11.35
| ChannelStore.GetMemberForPost | p99 | 20ms | 18ms | -2ms | -9.85
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 92ms | 83ms | -9ms | -9.81
| ChannelStore.GetPublicChannelsForTeam | p99 | 77ms | 70ms | -7ms | -9.10
| UserStore.Save | p99 | 231ms | 210ms | -21ms | -9.07
| ChannelStore.GetMemberCount | p99 | 90ms | 82ms | -8ms | -8.93
| GroupStore.GetGroups | p99 | 23ms | 21ms | -2ms | -8.52
| UserStore.GetAllProfiles | p99 | 24ms | 22ms | -2ms | -8.39
| PostStore.GetPostIdAfterTime | p99 | 24ms | 22ms | -2ms | -8.22
| UserStore.UpdateUpdateAt | p99 | 25ms | 23ms | -2ms | -8.06
| TeamStore.SaveMember | p99 | 99ms | 91ms | -8ms | -8.05
| ThreadStore.GetThreadsForUser | p99 | 25ms | 23ms | -2ms | -8.03
| ThreadStore.GetTotalThreads | p99 | 25ms | 23ms | -2ms | -7.85
| ChannelStore.Autocomplete | p99 | 108ms | 100ms | -8ms | -7.40
| PostStore.GetPostsSince | p99 | 79ms | 74ms | -5ms | -6.29
| ProductNoticesStore.View | p99 | 241ms | 226ms | -15ms | -6.22
| UserStore.GetAllProfilesInChannel | p99 | 948ms | 913ms | -35ms | -3.69
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 2ms | 2ms | 1579.67
| patchPost | avg | 108ms | 276ms | 168ms | 156.02
| createChannel | avg | 17ms | 29ms | 12ms | 72.08
| unfollowThreadByUser | avg | 9ms | 12ms | 3ms | 32.47
| searchPostsInTeam | avg | 161ms | 173ms | 12ms | 7.45
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | p99 | 25ms | 239ms | 214ms | 860.97
| unfollowThreadByUser | p99 | 24ms | 164ms | 140ms | 577.08
| getChannelUnread | p99 | 5ms | 19ms | 14ms | 282.83
| followThreadByUser | p99 | 10ms | 24ms | 14ms | 140.69
| logout | p99 | 98ms | 233ms | 135ms | 137.33
| patchPost | p99 | 235ms | 482ms | 247ms | 105.10
| createDirectChannel | p99 | 499ms | 623ms | 124ms | 24.87
| autocompleteUsers | p99 | 204ms | 225ms | 21ms | 10.29
| getChannelsForUser | p99 | 71ms | 73ms | 2ms | 2.82
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 13ms | 0s | -13ms | -102.18
| searchFiles | avg | 4ms | 0s | -4ms | -100.76
| getLicenseSelfServeStatus | avg | 66ms | 0s | -66ms | -100.42
| getAnalytics | avg | 24ms | 0s | -24ms | -100.13
| updateUserCustomStatus | avg | 192ms | 0s | -192ms | -99.87
| handleCheckCWSConnection | avg | 93ms | 0s | -93ms | -99.85
| getChannelMembersForUser | avg | 9ms | 0s | -9ms | -99.42
| createCategoryForTeamForUser | avg | 44ms | 0s | -44ms | -99.22
| upsertDraft | avg | 3ms | 0s | -3ms | -96.88
| getEmojisByNames | avg | 2ms | 0s | -2ms | -92.32
| getJobsByType | avg | 2ms | 0s | -2ms | -80.09
| autocompleteChannelsForTeamForSearch | avg | 34ms | 21ms | -13ms | -38.05
| getUsers | avg | 9ms | 6ms | -3ms | -34.11
| updateCategoriesForTeamForUser | avg | 69ms | 47ms | -22ms | -31.99
| createPost | avg | 413ms | 303ms | -110ms | -26.66
| getPostsForChannelAroundLastUnread | avg | 17ms | 13ms | -4ms | -23.86
| getPostsForChannel | avg | 22ms | 18ms | -4ms | -18.59
| addChannelMember | avg | 254ms | 219ms | -35ms | -13.78
| createGroupChannel | avg | 374ms | 326ms | -48ms | -12.85
| createDirectChannel | avg | 276ms | 241ms | -35ms | -12.70
| getCategoriesForTeamForUser | avg | 17ms | 15ms | -2ms | -11.91
| removeUserCustomStatus | avg | 190ms | 169ms | -21ms | -11.03
| saveReaction | avg | 20ms | 18ms | -2ms | -10.00
| addTeamMember | avg | 858ms | 785ms | -73ms | -8.51
| getProfileImage | avg | 97ms | 90ms | -7ms | -7.20
| createUser | avg | 103ms | 96ms | -7ms | -6.80
| getFileThumbnail | avg | 34ms | 32ms | -2ms | -5.97
| login | avg | 70ms | 67ms | -3ms | -4.29
| uploadFileStream | avg | 417ms | 406ms | -11ms | -2.64
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembersForUser | p99 | 25ms | 0s | -25ms | -101.83
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getRolesByNames | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| deleteDraft | p99 | 5ms | 0s | -5ms | -100.92
| upsertDraft | p99 | 5ms | 0s | -5ms | -100.90
| searchFiles | p99 | 5ms | 0s | -5ms | -100.89
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getLicenseSelfServeStatus | p99 | 100ms | 0s | -100ms | -100.50
| handleCheckCWSConnection | p99 | 100ms | 0s | -100ms | -100.50
| getAnalytics | p99 | 93ms | 0s | -93ms | -100.12
| createCategoryForTeamForUser | p99 | 244ms | 0s | -244ms | -100.00
| getJobsByType | p99 | 22ms | 0s | -22ms | -98.66
| updateUserCustomStatus | p99 | 487ms | 7ms | -480ms | -98.60
| getEmojisByNames | p99 | 23ms | 0s | -23ms | -98.38
| updateCategoriesForTeamForUser | p99 | 440ms | 97ms | -343ms | -77.95
| autocompleteChannelsForTeamForSearch | p99 | 235ms | 89ms | -146ms | -62.26
| getUsers | p99 | 172ms | 71ms | -101ms | -58.63
| saveReaction | p99 | 177ms | 96ms | -81ms | -45.67
| setPostReminder | p99 | 45ms | 25ms | -20ms | -44.69
| createPost | p99 | 2.404s | 1.463s | -941ms | -39.14
| getPostThread | p99 | 72ms | 46ms | -26ms | -36.31
| getAllTeams | p99 | 39ms | 25ms | -14ms | -35.96
| getTeamsForUser | p99 | 35ms | 23ms | -12ms | -34.75
| viewChannel | p99 | 76ms | 50ms | -26ms | -34.41
| createUser | p99 | 388ms | 257ms | -131ms | -33.75
| updatePreferences | p99 | 42ms | 28ms | -14ms | -32.99
| getPostsForChannelAroundLastUnread | p99 | 190ms | 130ms | -60ms | -31.61
| createGroupChannel | p99 | 971ms | 665ms | -306ms | -31.52
| getChannelMember | p99 | 78ms | 54ms | -24ms | -30.87
| getChannelMembersForTeamForUser | p99 | 33ms | 23ms | -10ms | -30.71
| updateReadStateThreadByUser | p99 | 164ms | 114ms | -50ms | -30.47
| getPreferences | p99 | 40ms | 28ms | -12ms | -30.34
| getThreadsForUser | p99 | 34ms | 24ms | -10ms | -29.00
| getChannel | p99 | 43ms | 31ms | -12ms | -27.67
| getTeamMembersForUser | p99 | 48ms | 36ms | -12ms | -25.20
| searchGroupChannels | p99 | 32ms | 24ms | -8ms | -24.82
| getChannelStats | p99 | 65ms | 50ms | -15ms | -23.20
| getUsersByIds | p99 | 9ms | 7ms | -2ms | -22.79
| getChannelsForTeamForUser | p99 | 31ms | 24ms | -7ms | -22.75
| getClientConfig | p99 | 76ms | 59ms | -17ms | -22.28
| getUsersByNames | p99 | 24ms | 19ms | -5ms | -21.09
| getUser | p99 | 48ms | 38ms | -10ms | -20.62
| getTeamsUnreadForUser | p99 | 49ms | 40ms | -9ms | -18.21
| searchAllChannels | p99 | 120ms | 100ms | -20ms | -16.68
| getPublicChannelsForTeam | p99 | 83ms | 70ms | -13ms | -15.72
| getPostsForChannel | p99 | 218ms | 188ms | -30ms | -13.79
| getCategoriesForTeamForUser | p99 | 93ms | 84ms | -9ms | -9.68
| login | p99 | 452ms | 419ms | -33ms | -7.31
| removeUserCustomStatus | p99 | 489ms | 478ms | -11ms | -2.25
| getFileThumbnail | p99 | 100ms | 98ms | -2ms | -2.01
| getProfileImage | p99 | 473ms | 464ms | -9ms | -1.90
| addChannelMember | p99 | 495ms | 488ms | -7ms | -1.41
| addTeamMember | p99 | 2.48s | 2.445s | -35ms | -1.41
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 3ms | -1ms | -26.283
| |  P99| 33ms| 24ms | -9ms | -27.435
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 72.354
| |  P99| 9ms| 10ms | 1ms | 11.050
| BotStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 78ms| 0s | -78ms | -100.122
| |  P99| 212ms| 0s | -212ms | -100.042
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.738
| ChannelStore.AnalyticsTypeCount |  Avg| 11ms| 0s | -11ms | -101.753
| |  P99| 25ms| 0s | -25ms | -100.929
| ChannelStore.Autocomplete |  Avg| 46ms| 45ms | -1ms | -2.168
| |  P99| 108ms| 100ms | -8ms | -7.404
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 34ms| 20ms | -14ms | -41.049
| |  P99| 235ms| 89ms | -146ms | -62.259
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 13ms | -3ms | -19.112
| |  P99| 120ms| 48ms | -72ms | -60.240
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 15ms | -2ms | -12.088
| |  P99| 155ms| 99ms | -56ms | -36.038
| ChannelStore.CreateSidebarCategory |  Avg| 30ms| 0s | -30ms | -100.828
| |  P99| 98ms| 0s | -98ms | -99.929
| ChannelStore.Get |  Avg| 2ms| 1ms | -1ms | -62.538
| |  P99| 24ms| 21ms | -3ms | -12.466
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 29.480
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 27ms| 25ms | -2ms | -7.408
| |  P99| 143ms| 98ms | -45ms | -31.540
| ChannelStore.GetByName |  Avg| 4ms| 3ms | -1ms | -28.060
| |  P99| 40ms| 29ms | -11ms | -27.246
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.360
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 2ms | -1ms | -28.719
| |  P99| 25ms| 9ms | -16ms | -65.075
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 1ms | -1ms | -62.127
| |  P99| 22ms| 17ms | -5ms | -22.850
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.548
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 33ms | -8ms | -19.591
| ChannelStore.GetMember |  Avg| 1ms| 2ms | 1ms | 67.051
| |  P99| 10ms| 22ms | 12ms | 123.106
| ChannelStore.GetMemberCount |  Avg| 23ms| 22ms | -1ms | -4.328
| |  P99| 90ms| 82ms | -8ms | -8.930
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.851
| ChannelStore.GetMembers |  Avg| 113ms| 0s | -113ms | -99.853
| |  P99| 466ms| 0s | -466ms | -100.080
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 22ms | -5ms | -18.322
| ChannelStore.GetMembersForUserWithPagination |  Avg| 16ms| 0s | -16ms | -99.234
| |  P99| 49ms| 0s | -49ms | -99.606
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 1ms | -1ms | -60.884
| |  P99| 25ms| 21ms | -4ms | -16.254
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 77ms| 70ms | -7ms | -9.096
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 17ms| 15ms | -2ms | -12.100
| |  P99| 92ms| 83ms | -9ms | -9.809
| ChannelStore.GetSidebarCategory |  Avg| 9ms| 8ms | -1ms | -11.166
| |  P99| 79ms| 25ms | -54ms | -68.356
| ChannelStore.GetTeamChannels |  Avg| 17ms| 24ms | 7ms | 42.397
| |  P99| 25ms| 96ms | 71ms | 285.649
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.398
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 7ms| 8ms | 1ms | 14.739
| |  P99| 32ms| 66ms | 34ms | 104.623
| ChannelStore.SaveMember |  Avg| 29ms| 27ms | -2ms | -6.795
| |  P99| 198ms| 153ms | -45ms | -22.767
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 3ms | -1ms | -27.554
| |  P99| 32ms| 24ms | -8ms | -24.819
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 3ms | -1ms | -28.309
| |  P99| 22ms| 18ms | -4ms | -18.133
| ChannelStore.UpdateSidebarCategories |  Avg| 49ms| 30ms | -19ms | -39.075
| |  P99| 438ms| 50ms | -388ms | -88.685
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.198
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 18ms | -12ms | -39.345
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 0s | -3ms | -104.075
| |  P99| 10ms| 0s | -10ms | -103.277
| DraftStore.Delete |  Avg| 2ms| 0s | -2ms | -91.078
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Get |  Avg| 1ms| 0s | -1ms | -125.880
| |  P99| 5ms| 0s | -5ms | -100.927
| DraftStore.GetDraftsForUser |  Avg| 1ms| 0s | -1ms | -75.775
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Upsert |  Avg| 2ms| 0s | -2ms | -85.257
| |  P99| 5ms| 0s | -5ms | -100.903
| EmojiStore.GetMultipleByName |  Avg| 4ms| 0s | -4ms | -92.168
| |  P99| 47ms| 0s | -47ms | -100.001
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 21ms | -14ms | -39.950
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.940
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 8ms | -4ms | -34.157
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -12.039
| FileInfoStore.Search |  Avg| 3ms| 0s | -3ms | -97.117
| |  P99| 5ms| 0s | -5ms | -100.887
| FileInfoStore.SetContent |  Avg| 7ms| 6ms | -1ms | -15.198
| |  P99| 40ms| 23ms | -17ms | -42.063
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 1ms | -1ms | -64.293
| |  P99| 24ms| 20ms | -4ms | -16.894
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 24ms | -12ms | -33.444
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.518
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 0s | -2ms | -112.091
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 43ms| 18ms | -25ms | -58.140
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 37ms | 5ms | 15.601
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -85.216
| |  P99| 22ms| 0s | -22ms | -98.657
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 37.175
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.328
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateOptimistically |  Avg| 3ms| 2ms | -1ms | -34.194
| |  P99| 16ms| 5ms | -11ms | -70.876
| JobStore.UpdateStatus |  Avg| 2ms| 3ms | 1ms | 42.919
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.306
| LinkMetadataStore.Save |  Avg| 3ms| 2ms | -1ms | -35.595
| |  P99| 17ms| 9ms | -8ms | -46.108
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -23.366
| PluginStore.Get |  Avg| 1ms| 2ms | 1ms | 150.697
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 11ms| 1ms | -10ms | -90.004
| |  P99| 51ms| 8ms | -43ms | -84.314
| PluginStore.SetWithOptions |  Avg| 5ms| 4ms | -1ms | -21.208
| |  P99| 43ms| 24ms | -19ms | -43.892
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -61.792
| |  P99| 25ms| 16ms | -9ms | -35.821
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 1ms | -1ms | -60.674
| |  P99| 23ms| 18ms | -5ms | -22.125
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.693
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -64.846
| |  P99| 50ms| 9ms | -41ms | -81.600
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 20ms | -4ms | -16.465
| PostStore.AnalyticsPostCount |  Avg| 1ms| 462ms | 461ms | 54366.477
| |  P99| 5ms| 498ms | 493ms | 9950.623
| PostStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 47ms | 22ms | 89.615
| PostStore.Get |  Avg| 4ms| 3ms | -1ms | -27.966
| |  P99| 35ms| 25ms | -10ms | -28.752
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 24ms | -6ms | -20.059
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.223
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 1ms | -1ms | -64.085
| |  P99| 20ms| 14ms | -6ms | -29.578
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.623
| PostStore.GetPostReminders |  Avg| 5ms| 3ms | -2ms | -40.050
| |  P99| 46ms| 5ms | -41ms | -89.617
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -26.935
| |  P99| 31ms| 24ms | -7ms | -22.923
| PostStore.GetPostsAfter |  Avg| 2ms| 3ms | 1ms | 42.082
| |  P99| 8ms| 19ms | 11ms | 131.729
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -11.924
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.245
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 79ms| 74ms | -5ms | -6.289
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 66ms| 48ms | -18ms | -27.150
| PostStore.SearchPostsForUser |  Avg| 153ms| 168ms | 15ms | 9.828
| |  P99| 2.339s| 2.342s | 3ms | 0.128
| PostStore.SetPostReminder |  Avg| 4ms| 5ms | 1ms | 24.776
| |  P99| 9ms| 10ms | 1ms | 10.554
| PostStore.Update |  Avg| 11ms| 10ms | -1ms | -9.372
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 64.012
| |  P99| 5ms| 9ms | 4ms | 80.780
| PreferenceStore.Get |  Avg| 2ms| 1ms | -1ms | -60.904
| |  P99| 24ms| 19ms | -5ms | -21.069
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 26ms | -11ms | -29.482
| PreferenceStore.Save |  Avg| 8ms| 7ms | -1ms | -12.293
| |  P99| 83ms| 58ms | -25ms | -30.104
| ProductNoticesStore.GetViews |  Avg| 6ms| 0s | -6ms | -97.651
| |  P99| 10ms| 0s | -10ms | -100.503
| ProductNoticesStore.View |  Avg| 30ms| 27ms | -3ms | -9.842
| |  P99| 241ms| 226ms | -15ms | -6.217
| ReactionStore.ExistsOnPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 16ms | -7ms | -31.055
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 13ms | -7ms | -34.427
| ReactionStore.GetUniqueCountForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 12ms | -6ms | -33.387
| ReactionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 51ms| 34ms | -17ms | -33.569
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -114.651
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -151.045
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 3ms | -1ms | -25.668
| |  P99| 21ms| 8ms | -13ms | -63.240
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -163.447
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 5ms| 4ms | -1ms | -19.924
| |  P99| 63ms| 47ms | -16ms | -25.237
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.617
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 5ms | -1ms | -16.873
| |  P99| 47ms| 39ms | -8ms | -16.987
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.299
| StatusStore.Get |  Avg| 2ms| 1ms | -1ms | -54.074
| |  P99| 26ms| 23ms | -3ms | -11.355
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.878
| StatusStore.SaveOrUpdate |  Avg| 34ms| 60ms | 26ms | 76.837
| |  P99| 497ms| 741ms | 244ms | 49.109
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 1ms | -2ms | -72.280
| |  P99| 46ms| 5ms | -41ms | -89.617
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 2ms | -1ms | -37.838
| |  P99| 21ms| 17ms | -4ms | -19.196
| SystemStore.GetByName |  Avg| 2ms| 1ms | -1ms | -56.944
| |  P99| 26ms| 21ms | -5ms | -19.051
| SystemStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 4ms | 3ms | 232.736
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.721
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 23ms | -8ms | -25.487
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.766
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 23ms | -8ms | -25.472
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 33ms| 23ms | -10ms | -29.917
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 24ms | -14ms | -37.276
| TeamStore.SaveMember |  Avg| 27ms| 25ms | -2ms | -7.512
| |  P99| 99ms| 91ms | -8ms | -8.050
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.393
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 16ms | -6ms | -27.640
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 3ms | -1ms | -28.084
| |  P99| 42ms| 25ms | -17ms | -40.944
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -15.221
| ThreadStore.GetThreadForUser |  Avg| 5ms| 4ms | -1ms | -21.882
| |  P99| 38ms| 25ms | -13ms | -33.880
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.066
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 3ms | -1ms | -28.243
| |  P99| 25ms| 23ms | -2ms | -8.032
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -7.852
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.180
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 23ms | -4ms | -14.721
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 2ms | -1ms | -39.654
| |  P99| 27ms| 23ms | -4ms | -14.801
| ThreadStore.MaintainMembership |  Avg| 4ms| 3ms | -1ms | -25.931
| |  P99| 32ms| 23ms | -9ms | -28.205
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -32.553
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.777
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 22ms | 14ms | 179.763
| UserStore.AnalyticsActiveCount |  Avg| 25ms| 0s | -25ms | -99.295
| |  P99| 49ms| 0s | -49ms | -99.240
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 0s | -1ms | -123.227
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 50ms| 49ms | -1ms | -2.018
| |  P99| 288ms| 316ms | 28ms | 9.729
| UserStore.Count |  Avg| 14ms| 15ms | 1ms | 7.120
| |  P99| 45ms| 46ms | 1ms | 2.210
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -35.932
| UserStore.GetAllProfiles |  Avg| 4ms| 3ms | -1ms | -26.954
| |  P99| 24ms| 22ms | -2ms | -8.387
| UserStore.GetAllProfilesInChannel |  Avg| 274ms| 257ms | -17ms | -6.214
| |  P99| 948ms| 913ms | -35ms | -3.692
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 22ms | -9ms | -28.800
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 24ms | -10ms | -29.340
| UserStore.GetMany |  Avg| 2ms| 1ms | -1ms | -43.806
| |  P99| 22ms| 9ms | -13ms | -57.870
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 20ms | -5ms | -20.140
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.076
| UserStore.GetProfilesInChannel |  Avg| 176ms| 185ms | 9ms | 5.123
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 18ms | -7ms | -28.028
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -15.067
| UserStore.Save |  Avg| 73ms| 70ms | -3ms | -4.125
| |  P99| 231ms| 210ms | -21ms | -9.073
| UserStore.Search |  Avg| 36ms| 35ms | -1ms | -2.745
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 69ms | 45ms | 185.610
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 30ms | -6ms | -16.590
| UserStore.UpdateUpdateAt |  Avg| 5ms| 4ms | -1ms | -20.913
| |  P99| 25ms| 23ms | -2ms | -8.057
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 1ms | -1ms | -57.837
| |  P99| 25ms| 22ms | -3ms | -11.852
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 28ms | -14ms | -33.076
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 254ms| 219ms | -35ms | -13.785
| | P99| 495ms| 488ms | -7ms | -1.414
| addTeamMember | Avg| 858ms| 785ms | -73ms | -8.510
| | P99| 2.48s| 2.445s | -35ms | -1.411
| autocompleteChannelsForTeamForSearch | Avg| 34ms| 21ms | -13ms | -38.054
| | P99| 235ms| 89ms | -146ms | -62.259
| autocompleteUsers | Avg| 42ms| 41ms | -1ms | -2.400
| | P99| 204ms| 225ms | 21ms | 10.292
| createCategoryForTeamForUser | Avg| 44ms| 0s | -44ms | -99.218
| | P99| 244ms| 0s | -244ms | -99.998
| createChannel | Avg| 17ms| 29ms | 12ms | 72.081
| | P99| 25ms| 239ms | 214ms | 860.970
| createDirectChannel | Avg| 276ms| 241ms | -35ms | -12.700
| | P99| 499ms| 623ms | 124ms | 24.866
| createGroupChannel | Avg| 374ms| 326ms | -48ms | -12.850
| | P99| 971ms| 665ms | -306ms | -31.519
| createPost | Avg| 413ms| 303ms | -110ms | -26.661
| | P99| 2.404s| 1.463s | -941ms | -39.141
| createUser | Avg| 103ms| 96ms | -7ms | -6.801
| | P99| 388ms| 257ms | -131ms | -33.754
| deleteDraft | Avg| 1ms| 0s | -1ms | -71.335
| | P99| 5ms| 0s | -5ms | -100.922
| deletePost | Avg| 14ms| 15ms | 1ms | 6.949
| | P99| 48ms| 47ms | -1ms | -2.062
| followThreadByUser | Avg| 8ms| 9ms | 1ms | 12.210
| | P99| 10ms| 24ms | 14ms | 140.687
| getAllTeams | Avg| 3ms| 2ms | -1ms | -38.427
| | P99| 39ms| 25ms | -14ms | -35.956
| getAnalytics | Avg| 24ms| 0s | -24ms | -100.131
| | P99| 93ms| 0s | -93ms | -100.118
| getCategoriesForTeamForUser | Avg| 17ms| 15ms | -2ms | -11.912
| | P99| 93ms| 84ms | -9ms | -9.684
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 43ms| 31ms | -12ms | -27.665
| getChannelMember | Avg| 7ms| 6ms | -1ms | -14.358
| | P99| 78ms| 54ms | -24ms | -30.872
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 33ms| 23ms | -10ms | -30.712
| getChannelMembersForUser | Avg| 9ms| 0s | -9ms | -99.423
| | P99| 25ms| 0s | -25ms | -101.833
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 65ms| 50ms | -15ms | -23.196
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 19ms | 14ms | 282.828
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -39.490
| | P99| 31ms| 24ms | -7ms | -22.749
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 71ms| 73ms | 2ms | 2.817
| getClientConfig | Avg| 6ms| 5ms | -1ms | -17.991
| | P99| 76ms| 59ms | -17ms | -22.279
| getClientLicense | Avg| 1ms| 0s | -1ms | -119.977
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 1ms| 0s | -1ms | -72.048
| | P99| 5ms| 0s | -5ms | -101.010
| getEmojisByNames | Avg| 2ms| 0s | -2ms | -92.320
| | P99| 23ms| 0s | -23ms | -98.375
| getFilePreview | Avg| 45ms| 44ms | -1ms | -2.231
| | P99| 217ms| 216ms | -1ms | -0.461
| getFileThumbnail | Avg| 34ms| 32ms | -2ms | -5.967
| | P99| 100ms| 98ms | -2ms | -2.007
| getFilteredUsersStats | Avg| 13ms| 0s | -13ms | -102.178
| | P99| 25ms| 0s | -25ms | -100.604
| getGroups | Avg| 1ms| 0s | -1ms | -83.870
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -80.090
| | P99| 22ms| 0s | -22ms | -98.657
| getLicenseSelfServeStatus | Avg| 66ms| 0s | -66ms | -100.423
| | P99| 100ms| 0s | -100ms | -100.503
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 72ms| 46ms | -26ms | -36.306
| getPostsForChannel | Avg| 22ms| 18ms | -4ms | -18.595
| | P99| 218ms| 188ms | -30ms | -13.788
| getPostsForChannelAroundLastUnread | Avg| 17ms| 13ms | -4ms | -23.855
| | P99| 190ms| 130ms | -60ms | -31.610
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 40ms| 28ms | -12ms | -30.342
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -111.250
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 97ms| 90ms | -7ms | -7.198
| | P99| 473ms| 464ms | -9ms | -1.902
| getPublicChannelsForTeam | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 83ms| 70ms | -13ms | -15.717
| getRolesByNames | Avg| 1ms| 0s | -1ms | -106.244
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.772
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 48ms| 36ms | -12ms | -25.204
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 35ms| 23ms | -12ms | -34.749
| getTeamsUnreadForUser | Avg| 5ms| 4ms | -1ms | -21.817
| | P99| 49ms| 40ms | -9ms | -18.213
| getThreadsForUser | Avg| 4ms| 3ms | -1ms | -26.277
| | P99| 34ms| 24ms | -10ms | -29.003
| getUser | Avg| 3ms| 2ms | -1ms | -32.943
| | P99| 48ms| 38ms | -10ms | -20.619
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 6ms | -3ms | -34.110
| | P99| 172ms| 71ms | -101ms | -58.633
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -22.794
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 19ms | -5ms | -21.093
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 93ms| 0s | -93ms | -99.851
| | P99| 100ms| 0s | -100ms | -100.503
| login | Avg| 70ms| 67ms | -3ms | -4.288
| | P99| 452ms| 419ms | -33ms | -7.306
| logout | Avg| 51ms| 52ms | 1ms | 1.977
| | P99| 98ms| 233ms | 135ms | 137.335
| patchPost | Avg| 108ms| 276ms | 168ms | 156.017
| | P99| 235ms| 482ms | 247ms | 105.100
| removeUserCustomStatus | Avg| 190ms| 169ms | -21ms | -11.034
| | P99| 489ms| 478ms | -11ms | -2.251
| root | Avg| 0s| 2ms | 2ms | 1579.673
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 20ms| 18ms | -2ms | -9.996
| | P99| 177ms| 96ms | -81ms | -45.674
| searchAllChannels | Avg| 46ms| 45ms | -1ms | -2.155
| | P99| 120ms| 100ms | -20ms | -16.684
| searchFiles | Avg| 4ms| 0s | -4ms | -100.757
| | P99| 5ms| 0s | -5ms | -100.887
| searchGroupChannels | Avg| 4ms| 3ms | -1ms | -27.080
| | P99| 32ms| 24ms | -8ms | -24.819
| searchPostsInTeam | Avg| 161ms| 173ms | 12ms | 7.446
| | P99| 2.357s| 2.348s | -9ms | -0.382
| searchUsers | Avg| 38ms| 37ms | -1ms | -2.608
| | P99| 99ms| 98ms | -1ms | -1.014
| setPostReminder | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 45ms| 25ms | -20ms | -44.693
| unfollowThreadByUser | Avg| 9ms| 12ms | 3ms | 32.465
| | P99| 24ms| 164ms | 140ms | 577.082
| updateCategoriesForTeamForUser | Avg| 69ms| 47ms | -22ms | -31.985
| | P99| 440ms| 97ms | -343ms | -77.954
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 42ms| 28ms | -14ms | -32.986
| updateReadStateThreadByUser | Avg| 31ms| 30ms | -1ms | -3.187
| | P99| 164ms| 114ms | -50ms | -30.471
| updateUserCustomStatus | Avg| 192ms| 0s | -192ms | -99.873
| | P99| 487ms| 7ms | -480ms | -98.596
| uploadFileStream | Avg| 417ms| 406ms | -11ms | -2.635
| | P99| 995ms| 993ms | -2ms | -0.201
| upsertDraft | Avg| 3ms| 0s | -3ms | -96.877
| | P99| 5ms| 0s | -5ms | -100.903
| viewChannel | Avg| 8ms| 7ms | -1ms | -12.807
| | P99| 76ms| 50ms | -26ms | -34.407
