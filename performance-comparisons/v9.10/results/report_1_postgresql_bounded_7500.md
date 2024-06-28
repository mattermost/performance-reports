### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 14ms | 12ms | 508.25
| UserStore.GetProfilesInChannel | avg | 32ms | 157ms | 125ms | 389.93
| RoleStore.ChannelHigherScopedPermissions | avg | 5ms | 7ms | 2ms | 40.72
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 21ms | 26ms | 5ms | 23.61
| PostStore.Delete | avg | 27ms | 30ms | 3ms | 10.93
| ChannelStore.CreateDirectChannel | avg | 25ms | 27ms | 2ms | 7.99
| UserStore.AutocompleteUsersInChannel | avg | 47ms | 50ms | 3ms | 6.32
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.UpdateStatus | p99 | 8ms | 78ms | 70ms | 903.23
| ThreadStore.Get | p99 | 9ms | 66ms | 57ms | 644.38
| PostStore.AnalyticsPostCount | p99 | 5ms | 25ms | 20ms | 403.76
| UserStore.GetProfilesInChannel | p99 | 50ms | 248ms | 198ms | 398.26
| UserStore.GetMany | p99 | 5ms | 24ms | 19ms | 383.84
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 24ms | 14ms | 145.27
| StatusStore.UpdateExpiredDNDStatuses | p99 | 9ms | 22ms | 13ms | 142.08
| JobStore.Save | p99 | 18ms | 39ms | 21ms | 114.13
| FileInfoStore.SetContent | p99 | 33ms | 71ms | 38ms | 113.43
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 19ms | 10ms | 112.68
| PostStore.GetPostsAfter | p99 | 21ms | 42ms | 21ms | 102.44
| ChannelStore.CreateDirectChannel | p99 | 93ms | 180ms | 87ms | 93.55
| ChannelStore.GetChannelUnread | p99 | 23ms | 41ms | 18ms | 76.60
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 9ms | 15ms | 6ms | 65.69
| RoleStore.ChannelHigherScopedPermissions | p99 | 23ms | 38ms | 15ms | 64.97
| ReactionStore.GetForPost | p99 | 22ms | 36ms | 14ms | 63.52
| FileInfoStore.Save | p99 | 25ms | 39ms | 14ms | 56.91
| StatusStore.GetByIds | p99 | 16ms | 23ms | 7ms | 45.14
| JobStore.GetAllByTypePage | p99 | 5ms | 7ms | 2ms | 40.40
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 133ms | 185ms | 52ms | 39.06
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 66ms | 17ms | 34.78
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 202ms | 233ms | 31ms | 15.31
| UserStore.GetAllProfiles | p99 | 26ms | 29ms | 3ms | 11.37
| ChannelStore.GetMember | p99 | 40ms | 44ms | 4ms | 10.00
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 36ms | 39ms | 3ms | 8.40
| FileInfoStore.AttachToPost | p99 | 45ms | 48ms | 3ms | 6.60
| ChannelStore.Save | p99 | 81ms | 86ms | 5ms | 6.15
| UserStore.GetProfileByIds | p99 | 35ms | 37ms | 2ms | 5.77
| PostPriorityStore.GetForPosts | p99 | 36ms | 38ms | 2ms | 5.50
| UserTermsOfServiceStore.GetByUser | p99 | 38ms | 40ms | 2ms | 5.21
| SessionStore.Get | p99 | 79ms | 83ms | 4ms | 5.09
| ChannelStore.GetMemberLastViewedAt | p99 | 40ms | 42ms | 2ms | 5.03
| PostStore.GetPosts | p99 | 40ms | 42ms | 2ms | 4.94
| UserStore.UpdateFailedPasswordAttempts | p99 | 43ms | 45ms | 2ms | 4.70
| PostStore.Save | p99 | 89ms | 92ms | 3ms | 3.37
| UserStore.AutocompleteUsersInChannel | p99 | 307ms | 314ms | 7ms | 2.28
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 4ms | 0s | -4ms | -111.22
| SystemStore.PermanentDeleteByName | avg | 3ms | 0s | -3ms | -106.49
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -104.94
| ChannelStore.CreateSidebarCategory | avg | 23ms | 0s | -23ms | -100.27
| ChannelStore.GetByNameIncludeDeleted | avg | 2ms | 0s | -2ms | -99.16
| FileInfoStore.Search | avg | 8ms | 0s | -8ms | -98.88
| UserStore.GetNewUsersForTeam | avg | 5ms | 0s | -5ms | -95.29
| SystemStore.SaveOrUpdate | avg | 3ms | 0s | -3ms | -93.02
| StatusStore.SaveOrUpdate | avg | 29ms | 4ms | -25ms | -85.65
| ChannelStore.SearchGroupChannels | avg | 14ms | 5ms | -9ms | -64.64
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 14ms | 5ms | -9ms | -63.15
| PreferenceStore.DeleteCategoryAndName | avg | 14ms | 5ms | -9ms | -62.53
| RetentionPolicyStore.GetAll | avg | 5ms | 2ms | -3ms | -58.16
| ChannelStore.AutocompleteInTeamForSearch | avg | 56ms | 24ms | -32ms | -57.22
| ChannelStore.GetSidebarCategory | avg | 20ms | 11ms | -9ms | -46.06
| ChannelStore.UpdateSidebarCategories | avg | 88ms | 48ms | -40ms | -45.28
| ChannelStore.CreateInitialSidebarCategories | avg | 50ms | 28ms | -22ms | -43.92
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 37ms | 21ms | -16ms | -43.72
| ChannelStore.GetTeamChannels | avg | 20ms | 15ms | -5ms | -24.50
| PostStore.Update | avg | 20ms | 15ms | -5ms | -24.42
| UserStore.AnalyticsActiveCount | avg | 24ms | 20ms | -4ms | -16.72
| TeamStore.GetTotalMemberCount | avg | 30ms | 28ms | -2ms | -6.64
| UserStore.GetRecentlyActiveUsersForTeam | avg | 47ms | 44ms | -3ms | -6.37
| PostStore.SearchPostsForUser | avg | 162ms | 156ms | -6ms | -3.71
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.54
| FileInfoStore.Search | p99 | 10ms | 0s | -10ms | -100.50
| UserStore.GetNewUsersForTeam | p99 | 10ms | 0s | -10ms | -100.50
| StatusStore.SaveOrUpdate | p99 | 436ms | 31ms | -405ms | -92.85
| PreferenceStore.DeleteCategoryAndName | p99 | 238ms | 24ms | -214ms | -89.92
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 238ms | 24ms | -214ms | -89.92
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.42s | 194ms | -1.226s | -86.34
| RetentionPolicyStore.GetAll | p99 | 24ms | 5ms | -19ms | -77.87
| ChannelStore.UpdateSidebarCategories | p99 | 440ms | 98ms | -342ms | -77.73
| ChannelStore.GetSidebarCategory | p99 | 93ms | 25ms | -68ms | -72.86
| PostStore.Update | p99 | 180ms | 49ms | -131ms | -72.68
| ThreadStore.MarkAllAsReadByChannels | p99 | 23ms | 8ms | -15ms | -65.50
| PostStore.Delete | p99 | 238ms | 97ms | -141ms | -59.24
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| RetentionPolicyStore.GetCount | p99 | 10ms | 5ms | -5ms | -51.28
| PluginStore.List | p99 | 41ms | 20ms | -21ms | -51.22
| PostAcknowledgementStore.GetForPost | p99 | 40ms | 20ms | -20ms | -49.61
| UserStore.AnalyticsActiveCount | p99 | 49ms | 25ms | -24ms | -49.32
| ChannelStore.GetTeamChannels | p99 | 49ms | 25ms | -24ms | -48.98
| ChannelStore.GetChannelsByUser | p99 | 80ms | 42ms | -38ms | -47.65
| UserStore.Update | p99 | 75ms | 41ms | -34ms | -45.63
| PostPriorityStore.GetForPost | p99 | 40ms | 22ms | -18ms | -44.65
| JobStore.GetCountByStatusAndType | p99 | 59ms | 33ms | -26ms | -44.07
| LinkMetadataStore.Save | p99 | 21ms | 12ms | -9ms | -43.74
| ChannelStore.SearchGroupChannels | p99 | 49ms | 28ms | -21ms | -43.25
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 167ms | 100ms | -67ms | -40.09
| UserStore.GetByUsername | p99 | 31ms | 19ms | -12ms | -39.18
| ComplianceStore.MessageExport | p99 | 40ms | 25ms | -15ms | -37.74
| ChannelStore.GetPinnedPostCount | p99 | 27ms | 17ms | -10ms | -37.38
| TeamStore.GetMember | p99 | 15ms | 10ms | -5ms | -34.41
| ClusterDiscoveryStore.SetLastPingAt | p99 | 35ms | 23ms | -12ms | -34.12
| ChannelStore.Autocomplete | p99 | 138ms | 100ms | -38ms | -27.46
| ThreadStore.UpdateMembership | p99 | 18ms | 14ms | -4ms | -22.48
| PreferenceStore.Save | p99 | 123ms | 99ms | -24ms | -19.56
| ThreadStore.MarkAsRead | p99 | 19ms | 16ms | -3ms | -15.81
| PostStore.GetPostsByThread | p99 | 28ms | 24ms | -4ms | -14.23
| ChannelStore.GetFileCount | p99 | 29ms | 25ms | -4ms | -13.90
| SessionStore.GetLRUSessions | p99 | 38ms | 33ms | -5ms | -13.06
| ChannelStore.GetMemberForPost | p99 | 33ms | 29ms | -4ms | -11.95
| SessionStore.Save | p99 | 69ms | 61ms | -8ms | -11.66
| PluginStore.Delete | p99 | 28ms | 25ms | -3ms | -10.72
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 48ms | 43ms | -5ms | -10.38
| PostStore.GetSingle | p99 | 20ms | 18ms | -2ms | -9.91
| PostStore.GetEtag | p99 | 41ms | 37ms | -4ms | -9.83
| ChannelStore.CreateInitialSidebarCategories | p99 | 241ms | 218ms | -23ms | -9.54
| LinkMetadataStore.Get | p99 | 21ms | 19ms | -2ms | -9.52
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 22ms | 20ms | -2ms | -9.29
| ProductNoticesStore.View | p99 | 311ms | 284ms | -27ms | -8.68
| ChannelStore.GetMembersForUser | p99 | 35ms | 32ms | -3ms | -8.62
| ThreadStore.GetTeamsUnreadForUser | p99 | 47ms | 43ms | -4ms | -8.59
| ChannelStore.GetAllChannelMembersForUser | p99 | 36ms | 33ms | -3ms | -8.44
| UserStore.UpdateLastLogin | p99 | 37ms | 34ms | -3ms | -8.17
| ThreadStore.GetTotalThreads | p99 | 38ms | 35ms | -3ms | -7.94
| ThreadStore.GetTotalUnreadMentions | p99 | 39ms | 36ms | -3ms | -7.69
| PluginStore.SetWithOptions | p99 | 58ms | 54ms | -4ms | -6.88
| ChannelStore.IncrementMentionCount | p99 | 33ms | 31ms | -2ms | -6.00
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 38ms | 36ms | -2ms | -5.20
| JobStore.GetAllByStatus | p99 | 40ms | 38ms | -2ms | -5.06
| TeamStore.GetTeamsForUser | p99 | 43ms | 41ms | -2ms | -4.68
| TeamStore.SaveMember | p99 | 191ms | 183ms | -8ms | -4.20
| ChannelStore.GetByName | p99 | 50ms | 48ms | -2ms | -4.02
| UserStore.GetAllProfilesInChannel | p99 | 953ms | 936ms | -17ms | -1.78
| ChannelStore.SaveMember | p99 | 236ms | 232ms | -4ms | -1.70
| PostStore.SearchPostsForUser | p99 | 2.313s | 2.278s | -35ms | -1.51
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 1ms | 3ms | 2ms | 367.22
| followThreadByUser | avg | 15ms | 30ms | 15ms | 103.11
| deleteDraft | avg | 3ms | 6ms | 3ms | 91.13
| getChannel | avg | 6ms | 10ms | 4ms | 68.99
| createChannel | avg | 238ms | 365ms | 127ms | 53.35
| createGroupChannel | avg | 404ms | 538ms | 134ms | 33.20
| getChannelMember | avg | 11ms | 14ms | 3ms | 27.44
| login | avg | 84ms | 103ms | 19ms | 22.64
| createUser | avg | 149ms | 181ms | 32ms | 21.45
| createDirectChannel | avg | 286ms | 333ms | 47ms | 16.41
| removeUserCustomStatus | avg | 186ms | 214ms | 28ms | 15.04
| addChannelMember | avg | 268ms | 306ms | 38ms | 14.19
| getTeamStats | avg | 52ms | 58ms | 6ms | 11.62
| autocompleteUsers | avg | 41ms | 43ms | 2ms | 4.87
| uploadFileStream | avg | 406ms | 421ms | 15ms | 3.70
| addTeamMember | avg | 984ms | 1.001s | 17ms | 1.73
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 25ms | 235ms | 210ms | 845.07
| getChannel | p99 | 16ms | 78ms | 62ms | 382.11
| setPostReminder | p99 | 25ms | 49ms | 24ms | 96.57
| getTeamMember | p99 | 24ms | 42ms | 18ms | 74.09
| createDirectChannel | p99 | 499ms | 868ms | 369ms | 73.88
| getChannelMember | p99 | 96ms | 148ms | 52ms | 54.45
| login | p99 | 489ms | 721ms | 232ms | 47.46
| uploadFileStream | p99 | 998ms | 1.413s | 415ms | 41.56
| getPublicChannelsForTeam | p99 | 49ms | 66ms | 17ms | 34.69
| createUser | p99 | 734ms | 849ms | 115ms | 15.66
| getChannelsForTeamForUser | p99 | 41ms | 46ms | 5ms | 12.18
| getUsersByNames | p99 | 27ms | 30ms | 3ms | 10.92
| getChannelStats | p99 | 50ms | 54ms | 4ms | 8.05
| getChannelUnread | p99 | 42ms | 45ms | 3ms | 7.06
| autocompleteUsers | p99 | 217ms | 230ms | 13ms | 5.98
| getUsers | p99 | 77ms | 81ms | 4ms | 5.19
| getTeamsForUser | p99 | 42ms | 44ms | 2ms | 4.79
| getPreferences | p99 | 44ms | 46ms | 2ms | 4.55
| getTeamsUnreadForUser | p99 | 72ms | 75ms | 3ms | 4.15
| getUser | p99 | 78ms | 81ms | 3ms | 3.86
| getClientConfig | p99 | 94ms | 97ms | 3ms | 3.18
| unfollowThreadByUser | p99 | 69ms | 71ms | 2ms | 2.88
| removeUserCustomStatus | p99 | 482ms | 491ms | 9ms | 1.87
| createChannel | p99 | 490ms | 498ms | 8ms | 1.63
| getFilePreview | p99 | 191ms | 194ms | 3ms | 1.57
| createGroupChannel | p99 | 980ms | 992ms | 12ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 3ms | 0s | -3ms | -119.05
| getDrafts | avg | 3ms | 0s | -3ms | -113.21
| getGroups | avg | 3ms | 0s | -3ms | -113.12
| getGroupsAssociatedToChannelsByTeam | avg | 3ms | 0s | -3ms | -104.89
| getChannelMembersForUser | avg | 10ms | 0s | -10ms | -104.56
| updateReadStateAllThreadsByUser | avg | 4ms | 0s | -4ms | -101.83
| updateCategoryForTeamForUser | avg | 81ms | 0s | -81ms | -99.86
| createCategoryForTeamForUser | avg | 25ms | 0s | -25ms | -98.37
| getChannelMembers | avg | 4ms | 0s | -4ms | -97.99
| searchFiles | avg | 10ms | 0s | -10ms | -96.92
| searchGroupChannels | avg | 14ms | 5ms | -9ms | -64.27
| autocompleteChannelsForTeamForSearch | avg | 56ms | 24ms | -32ms | -57.15
| updateCategoriesForTeamForUser | avg | 129ms | 71ms | -58ms | -45.12
| getChannelsForUser | avg | 7ms | 4ms | -3ms | -45.04
| getCategoriesForTeamForUser | avg | 37ms | 22ms | -15ms | -40.66
| getAnalytics | avg | 28ms | 20ms | -8ms | -29.09
| deletePost | avg | 60ms | 52ms | -8ms | -13.40
| patchPost | avg | 56ms | 51ms | -5ms | -8.95
| updateReadStateThreadByUser | avg | 49ms | 47ms | -2ms | -4.10
| logout | avg | 61ms | 59ms | -2ms | -3.27
| getProfileImage | avg | 92ms | 89ms | -3ms | -3.26
| searchPostsInTeam | avg | 173ms | 168ms | -5ms | -2.89
| createPost | avg | 366ms | 356ms | -10ms | -2.73
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembersForUser | p99 | 25ms | 0s | -25ms | -101.42
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -100.96
| searchFiles | p99 | 25ms | 0s | -25ms | -100.60
| updateCategoryForTeamForUser | p99 | 100ms | 0s | -100ms | -100.50
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| autocompleteChannelsForTeamForSearch | p99 | 1.42s | 194ms | -1.226s | -86.34
| updateCategoriesForTeamForUser | p99 | 473ms | 100ms | -373ms | -78.94
| getAnalytics | p99 | 227ms | 49ms | -178ms | -78.31
| upsertDraft | p99 | 24ms | 10ms | -14ms | -57.73
| deletePost | p99 | 480ms | 235ms | -245ms | -51.04
| getChannelsForUser | p99 | 85ms | 45ms | -40ms | -46.92
| searchGroupChannels | p99 | 49ms | 28ms | -21ms | -43.25
| searchAllChannels | p99 | 152ms | 101ms | -51ms | -33.66
| getCategoriesForTeamForUser | p99 | 175ms | 121ms | -54ms | -30.93
| updateReadStateThreadByUser | p99 | 229ms | 178ms | -51ms | -22.29
| patchPost | p99 | 847ms | 733ms | -114ms | -13.46
| getTeamMembersForUser | p99 | 57ms | 52ms | -5ms | -8.73
| addChannelMember | p99 | 925ms | 856ms | -69ms | -7.46
| saveReaction | p99 | 89ms | 84ms | -5ms | -5.60
| createPost | p99 | 2.157s | 2.055s | -102ms | -4.73
| updatePreferences | p99 | 48ms | 46ms | -2ms | -4.16
| getProfileImage | p99 | 474ms | 462ms | -12ms | -2.53
| getPostsForChannel | p99 | 239ms | 234ms | -5ms | -2.09
| getPostThread | p99 | 97ms | 95ms | -2ms | -2.05
| addTeamMember | p99 | 3.904s | 3.835s | -69ms | -1.77
| getPostsForChannelAroundLastUnread | p99 | 229ms | 225ms | -4ms | -1.75
| logout | p99 | 238ms | 235ms | -3ms | -1.26
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.304
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.554
| BotStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 76ms| 76ms | 0s | 0.000
| |  P99| 133ms| 185ms | 52ms | 39.062
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 33ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 47ms| 47ms | 0s | 0.000
| |  P99| 138ms| 100ms | -38ms | -27.456
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 56ms| 24ms | -32ms | -57.216
| |  P99| 1.42s| 194ms | -1.226s | -86.340
| ChannelStore.CreateDirectChannel |  Avg| 25ms| 27ms | 2ms | 7.987
| |  P99| 93ms| 180ms | 87ms | 93.551
| ChannelStore.CreateInitialSidebarCategories |  Avg| 50ms| 28ms | -22ms | -43.917
| |  P99| 241ms| 218ms | -23ms | -9.540
| ChannelStore.CreateSidebarCategory |  Avg| 23ms| 0s | -23ms | -100.268
| |  P99| 25ms| 0s | -25ms | -100.537
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 35ms | -1ms | -2.766
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 43ms | -5ms | -10.384
| ChannelStore.GetAllChannelMembersForUser |  Avg| 7ms| 6ms | -1ms | -15.277
| |  P99| 36ms| 33ms | -3ms | -8.437
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 21ms| 26ms | 5ms | 23.608
| |  P99| 202ms| 233ms | 31ms | 15.314
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 48ms | -2ms | -4.022
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 0s | -2ms | -99.159
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 3ms| 4ms | 1ms | 28.685
| |  P99| 23ms| 41ms | 18ms | 76.596
| ChannelStore.GetChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 33ms | -1ms | -2.985
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 4ms | -1ms | -19.622
| |  P99| 80ms| 42ms | -38ms | -47.649
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.899
| ChannelStore.GetGuestCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 4ms| 5ms | 1ms | 23.874
| |  P99| 40ms| 44ms | 4ms | 9.996
| ChannelStore.GetMemberCount |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 88ms| 87ms | -1ms | -1.132
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 33ms| 29ms | -4ms | -11.949
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 5.029
| ChannelStore.GetMembers |  Avg| 4ms| 0s | -4ms | -111.223
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 32ms | -3ms | -8.622
| ChannelStore.GetMembersForUserWithPagination |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.228
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 2ms | -1ms | -37.229
| |  P99| 27ms| 17ms | -10ms | -37.383
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 49ms| 66ms | 17ms | 34.780
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 37ms| 21ms | -16ms | -43.721
| |  P99| 167ms| 100ms | -67ms | -40.087
| ChannelStore.GetSidebarCategory |  Avg| 20ms| 11ms | -9ms | -46.057
| |  P99| 93ms| 25ms | -68ms | -72.857
| ChannelStore.GetTeamChannels |  Avg| 20ms| 15ms | -5ms | -24.495
| |  P99| 49ms| 25ms | -24ms | -48.978
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 31ms | -2ms | -6.002
| ChannelStore.Save |  Avg| 14ms| 15ms | 1ms | 7.356
| |  P99| 81ms| 86ms | 5ms | 6.154
| ChannelStore.SaveMember |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 236ms| 232ms | -4ms | -1.696
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 5ms | -9ms | -64.642
| |  P99| 49ms| 28ms | -21ms | -43.248
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 88ms| 48ms | -40ms | -45.281
| |  P99| 440ms| 98ms | -342ms | -77.727
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 15ms | 6ms | 65.693
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 23ms | -12ms | -34.123
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 5ms| 4ms | -1ms | -21.675
| |  P99| 40ms| 25ms | -15ms | -37.736
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 14ms| 5ms | -9ms | -63.155
| |  P99| 238ms| 24ms | -214ms | -89.916
| DraftStore.Get |  Avg| 2ms| 3ms | 1ms | 44.552
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.091
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 48ms | 3ms | 6.597
| FileInfoStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.030
| FileInfoStore.Save |  Avg| 5ms| 6ms | 1ms | 18.487
| |  P99| 25ms| 39ms | 14ms | 56.910
| FileInfoStore.Search |  Avg| 8ms| 0s | -8ms | -98.880
| |  P99| 10ms| 0s | -10ms | -100.503
| FileInfoStore.SetContent |  Avg| 9ms| 10ms | 1ms | 11.691
| |  P99| 33ms| 71ms | 38ms | 113.433
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 39ms | 3ms | 8.399
| GroupStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.268
| GroupStore.GetGroups |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 29ms | -1ms | -3.333
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 2ms | -1ms | -36.416
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 3ms | 1ms | 40.654
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 38ms | -2ms | -5.060
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| JobStore.GetCountByStatusAndType |  Avg| 4ms| 3ms | -1ms | -28.205
| |  P99| 59ms| 33ms | -26ms | -44.068
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 3ms | 1ms | 40.263
| |  P99| 10ms| 24ms | 14ms | 145.266
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 39ms | 21ms | 114.130
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 5ms | 1ms | 28.540
| |  P99| 8ms| 78ms | 70ms | 903.226
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 112.676
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 3ms| 2ms | -1ms | -39.564
| |  P99| 21ms| 19ms | -2ms | -9.516
| LinkMetadataStore.Save |  Avg| 5ms| 4ms | -1ms | -22.011
| |  P99| 21ms| 12ms | -9ms | -43.742
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.716
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 4ms| 3ms | -1ms | -25.963
| |  P99| 41ms| 20ms | -21ms | -51.220
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 58ms| 54ms | -4ms | -6.876
| PostAcknowledgementStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -24.608
| |  P99| 40ms| 20ms | -20ms | -49.612
| PostAcknowledgementStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 35ms | 1ms | 2.978
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -26.789
| |  P99| 40ms| 22ms | -18ms | -44.651
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 38ms | 2ms | 5.499
| PostStore.AnalyticsPostCount |  Avg| 2ms| 14ms | 12ms | 508.252
| |  P99| 5ms| 25ms | 20ms | 403.757
| PostStore.Delete |  Avg| 27ms| 30ms | 3ms | 10.933
| |  P99| 238ms| 97ms | -141ms | -59.244
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 37ms | -4ms | -9.834
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.850
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.051
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 5ms| 6ms | 1ms | 18.410
| |  P99| 40ms| 42ms | 2ms | 4.942
| PostStore.GetPostsAfter |  Avg| 4ms| 5ms | 1ms | 26.976
| |  P99| 21ms| 42ms | 21ms | 102.439
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 33ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.227
| PostStore.GetPostsSince |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 78ms| 78ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.914
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 89ms| 92ms | 3ms | 3.369
| PostStore.SearchPostsForUser |  Avg| 162ms| 156ms | -6ms | -3.714
| |  P99| 2.313s| 2.278s | -35ms | -1.513
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 20ms| 15ms | -5ms | -24.424
| |  P99| 180ms| 49ms | -131ms | -72.677
| PreferenceStore.DeleteCategoryAndName |  Avg| 14ms| 5ms | -9ms | -62.534
| |  P99| 238ms| 24ms | -214ms | -89.916
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 31ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 123ms| 99ms | -24ms | -19.559
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 311ms| 284ms | -27ms | -8.679
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 36ms | 14ms | 63.522
| RetentionPolicyStore.GetAll |  Avg| 5ms| 2ms | -3ms | -58.161
| |  P99| 24ms| 5ms | -19ms | -77.869
| RetentionPolicyStore.GetCount |  Avg| 2ms| 1ms | -1ms | -53.041
| |  P99| 10ms| 5ms | -5ms | -51.282
| RoleStore.ChannelHigherScopedPermissions |  Avg| 5ms| 7ms | 2ms | 40.719
| |  P99| 23ms| 38ms | 15ms | 64.970
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 9ms | 1ms | 12.319
| |  P99| 79ms| 83ms | 4ms | 5.091
| SessionStore.GetLRUSessions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 33ms | -5ms | -13.059
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.294
| SessionStore.Remove |  Avg| 5ms| 4ms | -1ms | -18.332
| |  P99| 24ms| 23ms | -1ms | -4.202
| SessionStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 69ms| 61ms | -8ms | -11.658
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 5ms | 1ms | 22.314
| |  P99| 24ms| 24ms | 0s | 0.000
| StatusStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 23ms | 7ms | 45.137
| StatusStore.SaveOrUpdate |  Avg| 29ms| 4ms | -25ms | -85.646
| |  P99| 436ms| 31ms | -405ms | -92.853
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 3ms | 1ms | 46.669
| |  P99| 9ms| 22ms | 13ms | 142.077
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| SystemStore.PermanentDeleteByName |  Avg| 3ms| 0s | -3ms | -106.491
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 3ms| 0s | -3ms | -93.019
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 3ms| 2ms | -1ms | -39.807
| |  P99| 21ms| 20ms | -1ms | -4.677
| TeamStore.GetActiveMemberCount |  Avg| 51ms| 51ms | 0s | 0.000
| |  P99| 99ms| 100ms | 1ms | 1.007
| TeamStore.GetAllPage |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -34.410
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.684
| TeamStore.GetTotalMemberCount |  Avg| 30ms| 28ms | -2ms | -6.635
| |  P99| 49ms| 50ms | 1ms | 2.041
| TeamStore.SaveMember |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 191ms| 183ms | -8ms | -4.199
| ThreadStore.Get |  Avg| 2ms| 3ms | 1ms | 46.283
| |  P99| 9ms| 66ms | 57ms | 644.377
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.075
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 43ms | -4ms | -8.586
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 42ms| 43ms | 1ms | 2.379
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.841
| ThreadStore.GetTotalThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 35ms | -3ms | -7.942
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.692
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 35ms | -1ms | -2.766
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.204
| ThreadStore.MaintainMembership |  Avg| 6ms| 7ms | 1ms | 15.486
| |  P99| 46ms| 46ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 3ms | -1ms | -26.292
| |  P99| 23ms| 8ms | -15ms | -65.502
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -104.937
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.808
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 14ms | -4ms | -22.475
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 24ms| 20ms | -4ms | -16.720
| |  P99| 49ms| 25ms | -24ms | -49.315
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 47ms| 50ms | 3ms | 6.316
| |  P99| 307ms| 314ms | 7ms | 2.282
| UserStore.Count |  Avg| 15ms| 14ms | -1ms | -6.554
| |  P99| 46ms| 45ms | -1ms | -2.151
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 26ms| 29ms | 3ms | 11.374
| UserStore.GetAllProfilesInChannel |  Avg| 269ms| 267ms | -2ms | -0.743
| |  P99| 953ms| 936ms | -17ms | -1.783
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 19ms | -12ms | -39.184
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.312
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 45.408
| |  P99| 5ms| 24ms | 19ms | 383.838
| UserStore.GetNewUsersForTeam |  Avg| 5ms| 0s | -5ms | -95.288
| |  P99| 10ms| 0s | -10ms | -100.503
| UserStore.GetProfileByIds |  Avg| 3ms| 4ms | 1ms | 29.095
| |  P99| 35ms| 37ms | 2ms | 5.774
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.775
| UserStore.GetProfilesInChannel |  Avg| 32ms| 157ms | 125ms | 389.930
| |  P99| 50ms| 248ms | 198ms | 398.257
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetRecentlyActiveUsersForTeam |  Avg| 47ms| 44ms | -3ms | -6.365
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 3ms | -1ms | -27.718
| |  P99| 24ms| 25ms | 1ms | 4.178
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.238
| UserStore.Save |  Avg| 76ms| 76ms | 0s | 0.000
| |  P99| 236ms| 237ms | 1ms | 0.423
| UserStore.Search |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 9ms| 8ms | -1ms | -11.680
| |  P99| 75ms| 41ms | -34ms | -45.627
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.704
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 37ms| 34ms | -3ms | -8.174
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.605
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.212
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 268ms| 306ms | 38ms | 14.186
| | P99| 925ms| 856ms | -69ms | -7.459
| addTeamMember | Avg| 984ms| 1.001s | 17ms | 1.727
| | P99| 3.904s| 3.835s | -69ms | -1.767
| autocompleteChannelsForTeamForSearch | Avg| 56ms| 24ms | -32ms | -57.151
| | P99| 1.42s| 194ms | -1.226s | -86.340
| autocompleteUsers | Avg| 41ms| 43ms | 2ms | 4.867
| | P99| 217ms| 230ms | 13ms | 5.985
| createCategoryForTeamForUser | Avg| 25ms| 0s | -25ms | -98.369
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 238ms| 365ms | 127ms | 53.345
| | P99| 490ms| 498ms | 8ms | 1.633
| createDirectChannel | Avg| 286ms| 333ms | 47ms | 16.406
| | P99| 499ms| 868ms | 369ms | 73.879
| createGroupChannel | Avg| 404ms| 538ms | 134ms | 33.203
| | P99| 980ms| 992ms | 12ms | 1.225
| createPost | Avg| 366ms| 356ms | -10ms | -2.735
| | P99| 2.157s| 2.055s | -102ms | -4.729
| createUser | Avg| 149ms| 181ms | 32ms | 21.454
| | P99| 734ms| 849ms | 115ms | 15.665
| deleteDraft | Avg| 3ms| 6ms | 3ms | 91.129
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 60ms| 52ms | -8ms | -13.398
| | P99| 480ms| 235ms | -245ms | -51.042
| followThreadByUser | Avg| 15ms| 30ms | 15ms | 103.109
| | P99| 25ms| 235ms | 210ms | 845.070
| getAllTeams | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.102
| getAnalytics | Avg| 28ms| 20ms | -8ms | -29.088
| | P99| 227ms| 49ms | -178ms | -78.307
| getCategoriesForTeamForUser | Avg| 37ms| 22ms | -15ms | -40.663
| | P99| 175ms| 121ms | -54ms | -30.930
| getChannel | Avg| 6ms| 10ms | 4ms | 68.994
| | P99| 16ms| 78ms | 62ms | 382.106
| getChannelMember | Avg| 11ms| 14ms | 3ms | 27.441
| | P99| 96ms| 148ms | 52ms | 54.447
| getChannelMembers | Avg| 4ms| 0s | -4ms | -97.992
| | P99| 5ms| 0s | -5ms | -100.956
| getChannelMembersForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 41ms| 42ms | 1ms | 2.442
| getChannelMembersForUser | Avg| 10ms| 0s | -10ms | -104.556
| | P99| 25ms| 0s | -25ms | -101.420
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 50ms| 54ms | 4ms | 8.051
| getChannelUnread | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 42ms| 45ms | 3ms | 7.059
| getChannelsForTeamForUser | Avg| 4ms| 5ms | 1ms | 23.188
| | P99| 41ms| 46ms | 5ms | 12.184
| getChannelsForUser | Avg| 7ms| 4ms | -3ms | -45.043
| | P99| 85ms| 45ms | -40ms | -46.921
| getClientConfig | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 94ms| 97ms | 3ms | 3.182
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 0s | -3ms | -113.207
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 44ms| 44ms | 0s | 0.000
| | P99| 191ms| 194ms | 3ms | 1.571
| getFileThumbnail | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| getFilteredUsersStats | Avg| 13ms| 14ms | 1ms | 7.564
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 3ms| 0s | -3ms | -113.116
| | P99| 5ms| 0s | -5ms | -101.010
| getGroupsAssociatedToChannelsByTeam | Avg| 3ms| 0s | -3ms | -104.894
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.423
| getPostThread | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 97ms| 95ms | -2ms | -2.053
| getPostsForChannel | Avg| 31ms| 30ms | -1ms | -3.191
| | P99| 239ms| 234ms | -5ms | -2.093
| getPostsForChannelAroundLastUnread | Avg| 27ms| 28ms | 1ms | 3.663
| | P99| 229ms| 225ms | -4ms | -1.750
| getPreferences | Avg| 5ms| 6ms | 1ms | 19.585
| | P99| 44ms| 46ms | 2ms | 4.546
| getPrevTrialLicense | Avg| 1ms| 2ms | 1ms | 67.535
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 3ms| 0s | -3ms | -119.053
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 92ms| 89ms | -3ms | -3.259
| | P99| 474ms| 462ms | -12ms | -2.529
| getPublicChannelsForTeam | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 49ms| 66ms | 17ms | 34.692
| getRolesByNames | Avg| 1ms| 3ms | 2ms | 367.220
| | P99| 9ms| 10ms | 1ms | 10.695
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 4ms | 1ms | 35.211
| | P99| 24ms| 42ms | 18ms | 74.089
| getTeamMembersForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 57ms| 52ms | -5ms | -8.734
| getTeamStats | Avg| 52ms| 58ms | 6ms | 11.616
| | P99| 99ms| 100ms | 1ms | 1.007
| getTeamsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 42ms| 44ms | 2ms | 4.785
| getTeamsUnreadForUser | Avg| 7ms| 8ms | 1ms | 13.688
| | P99| 72ms| 75ms | 3ms | 4.152
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 42ms| 43ms | 1ms | 2.377
| getUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 78ms| 81ms | 3ms | 3.858
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 8ms | 1ms | 14.110
| | P99| 77ms| 81ms | 4ms | 5.188
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 27ms| 30ms | 3ms | 10.920
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 84ms| 103ms | 19ms | 22.644
| | P99| 489ms| 721ms | 232ms | 47.455
| logout | Avg| 61ms| 59ms | -2ms | -3.266
| | P99| 238ms| 235ms | -3ms | -1.261
| patchPost | Avg| 56ms| 51ms | -5ms | -8.948
| | P99| 847ms| 733ms | -114ms | -13.465
| removeUserCustomStatus | Avg| 186ms| 214ms | 28ms | 15.037
| | P99| 482ms| 491ms | 9ms | 1.867
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 14ms| 13ms | -1ms | -7.368
| | P99| 89ms| 84ms | -5ms | -5.603
| searchAllChannels | Avg| 47ms| 47ms | 0s | 0.000
| | P99| 152ms| 101ms | -51ms | -33.657
| searchFiles | Avg| 10ms| 0s | -10ms | -96.924
| | P99| 25ms| 0s | -25ms | -100.604
| searchGroupChannels | Avg| 14ms| 5ms | -9ms | -64.271
| | P99| 49ms| 28ms | -21ms | -43.248
| searchPostsInTeam | Avg| 173ms| 168ms | -5ms | -2.894
| | P99| 2.34s| 2.326s | -14ms | -0.598
| searchUsers | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 20ms| 21ms | 1ms | 4.903
| | P99| 25ms| 49ms | 24ms | 96.573
| unfollowThreadByUser | Avg| 15ms| 16ms | 1ms | 6.475
| | P99| 69ms| 71ms | 2ms | 2.878
| updateCategoriesForTeamForUser | Avg| 129ms| 71ms | -58ms | -45.115
| | P99| 473ms| 100ms | -373ms | -78.942
| updateCategoryForTeamForUser | Avg| 81ms| 0s | -81ms | -99.857
| | P99| 100ms| 0s | -100ms | -100.503
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 48ms| 46ms | -2ms | -4.156
| updateReadStateAllThreadsByUser | Avg| 4ms| 0s | -4ms | -101.829
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 49ms| 47ms | -2ms | -4.099
| | P99| 229ms| 178ms | -51ms | -22.295
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 406ms| 421ms | 15ms | 3.698
| | P99| 998ms| 1.413s | 415ms | 41.563
| upsertDraft | Avg| 5ms| 4ms | -1ms | -22.162
| | P99| 24ms| 10ms | -14ms | -57.727
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
