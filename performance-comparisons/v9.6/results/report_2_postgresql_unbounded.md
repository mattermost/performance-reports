### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 1ms | 16ms | 15ms | 1270.15
| DraftStore.GetDraftsForUser | avg | 4ms | 27ms | 23ms | 605.85
| PluginStore.Get | avg | 3ms | 9ms | 6ms | 236.98
| ChannelStore.GetByNameIncludeDeleted | avg | 1ms | 4ms | 3ms | 226.70
| CommandWebhookStore.Cleanup | avg | 2ms | 5ms | 3ms | 194.92
| TeamStore.AnalyticsTeamCount | avg | 6ms | 14ms | 8ms | 128.94
| StatusStore.SaveOrUpdate | avg | 52ms | 111ms | 59ms | 114.27
| ChannelStore.GetMembers | avg | 5ms | 10ms | 5ms | 95.05
| LicenseStore.GetAll | avg | 4ms | 7ms | 3ms | 80.20
| ChannelStore.GetMembersForUserWithPagination | avg | 23ms | 39ms | 16ms | 69.05
| PostStore.AnalyticsPostCount | avg | 237ms | 398ms | 161ms | 67.96
| UserStore.AnalyticsGetInactiveUsersCount | avg | 4ms | 6ms | 2ms | 52.69
| ChannelStore.CreateInitialSidebarCategories | avg | 37ms | 55ms | 18ms | 48.75
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 31ms | 45ms | 14ms | 44.82
| ChannelStore.SearchGroupChannels | avg | 14ms | 20ms | 6ms | 44.31
| UserStore.GetByUsername | avg | 8ms | 11ms | 3ms | 37.54
| SessionStore.Remove | avg | 9ms | 11ms | 2ms | 22.39
| UserStore.Update | avg | 16ms | 19ms | 3ms | 18.77
| ChannelStore.AutocompleteInTeamForSearch | avg | 103ms | 119ms | 16ms | 15.55
| ChannelStore.GetTeamChannels | avg | 27ms | 30ms | 3ms | 11.17
| ProductNoticesStore.ClearOldNotices | avg | 35ms | 37ms | 2ms | 5.69
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 346ms | 3.595s | 3.249s | 940.05
| PluginStore.Get | p99 | 9ms | 49ms | 40ms | 421.05
| DraftStore.GetDraftsForUser | p99 | 10ms | 50ms | 40ms | 404.04
| TokenStore.Cleanup | p99 | 5ms | 25ms | 20ms | 404.02
| TeamStore.AnalyticsTeamCount | p99 | 24ms | 96ms | 72ms | 300.64
| UserStore.GetByUsername | p99 | 60ms | 162ms | 102ms | 170.95
| ChannelStore.GetMembersForUserWithPagination | p99 | 89ms | 235ms | 146ms | 164.97
| LicenseStore.GetAll | p99 | 23ms | 48ms | 25ms | 109.17
| ChannelStore.GetMembers | p99 | 24ms | 49ms | 25ms | 103.74
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 24ms | 49ms | 25ms | 103.09
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.00
| PostStore.AnalyticsPostCount | p99 | 495ms | 990ms | 495ms | 100.00
| ChannelStore.GetTeamChannels | p99 | 49ms | 97ms | 48ms | 97.06
| UserAccessTokenStore.GetByToken | p99 | 44ms | 85ms | 41ms | 92.79
| JobStore.GetAllByTypePage | p99 | 48ms | 92ms | 44ms | 92.14
| JobStore.GetCountByStatusAndType | p99 | 46ms | 87ms | 41ms | 88.17
| StatusStore.UpdateExpiredDNDStatuses | p99 | 49ms | 89ms | 40ms | 81.80
| JobStore.Save | p99 | 42ms | 73ms | 31ms | 73.16
| JobStore.GetNewestJobByStatusesAndType | p99 | 46ms | 77ms | 31ms | 67.12
| ChannelStore.Save | p99 | 245ms | 346ms | 101ms | 41.17
| LinkMetadataStore.Save | p99 | 99ms | 138ms | 39ms | 39.42
| ClusterDiscoveryStore.SetLastPingAt | p99 | 70ms | 96ms | 26ms | 36.88
| StatusStore.SaveOrUpdate | p99 | 870ms | 981ms | 111ms | 12.76
| TeamStore.GetMember | p99 | 35ms | 39ms | 4ms | 11.43
| JobStore.GetAllByStatus | p99 | 95ms | 105ms | 10ms | 10.57
| SessionStore.Remove | p99 | 85ms | 93ms | 8ms | 9.36
| TeamStore.GetByName | p99 | 69ms | 74ms | 5ms | 7.29
| BotStore.Get | p99 | 44ms | 47ms | 3ms | 6.82
| ChannelStore.SearchGroupChannels | p99 | 128ms | 134ms | 6ms | 4.70
| UserStore.Update | p99 | 210ms | 217ms | 7ms | 3.33
| ChannelStore.AnalyticsTypeCount | p99 | 94ms | 97ms | 3ms | 3.19
| FileInfoStore.SetContent | p99 | 183ms | 187ms | 4ms | 2.18
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 15ms | 0s | -15ms | -102.56
| ChannelStore.CreateSidebarCategory | avg | 35ms | 0s | -35ms | -100.69
| ChannelStore.GetMemberCountsByGroup | avg | 11ms | 0s | -11ms | -99.60
| EmojiStore.Search | avg | 39ms | 0s | -39ms | -98.77
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 16ms | 2ms | -14ms | -87.16
| SessionStore.GetSessionsExpired | avg | 28ms | 4ms | -24ms | -84.92
| DraftStore.Get | avg | 5ms | 1ms | -4ms | -84.55
| UserStore.GetProfilesInChannel | avg | 272ms | 58ms | -214ms | -78.79
| RetentionPolicyStore.GetCount | avg | 11ms | 3ms | -8ms | -75.62
| JobStore.UpdateStatus | avg | 11ms | 3ms | -8ms | -71.84
| JobStore.UpdateStatusOptimistically | avg | 13ms | 4ms | -9ms | -69.67
| PostStore.GetPostReminders | avg | 18ms | 7ms | -11ms | -61.28
| PostPersistentNotificationStore.DeleteExpired | avg | 5ms | 2ms | -3ms | -61.08
| PostPersistentNotificationStore.Get | avg | 7ms | 3ms | -4ms | -53.88
| PreferenceStore.DeleteCategoryAndName | avg | 14ms | 7ms | -7ms | -49.70
| RetentionPolicyStore.GetAll | avg | 4ms | 2ms | -2ms | -49.49
| LinkMetadataStore.Save | avg | 10ms | 6ms | -4ms | -41.90
| PostPriorityStore.GetForPost | avg | 9ms | 6ms | -3ms | -34.90
| PluginStore.List | avg | 9ms | 6ms | -3ms | -34.46
| BotStore.Get | avg | 9ms | 6ms | -3ms | -32.34
| UserStore.AnalyticsActiveCount | avg | 64ms | 44ms | -20ms | -31.38
| PostStore.GetPostReminderMetadata | avg | 14ms | 10ms | -4ms | -29.18
| PostStore.Update | avg | 31ms | 23ms | -8ms | -26.09
| StatusStore.GetByIds | avg | 12ms | 9ms | -3ms | -24.40
| PostAcknowledgementStore.GetForPost | avg | 8ms | 6ms | -2ms | -23.73
| ChannelStore.AnalyticsTypeCount | avg | 27ms | 21ms | -6ms | -22.46
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 36ms | 29ms | -7ms | -19.45
| ChannelStore.CreateDirectChannel | avg | 64ms | 52ms | -12ms | -18.90
| ChannelStore.GetSidebarCategory | avg | 22ms | 18ms | -4ms | -18.34
| PostStore.GetPostsAfter | avg | 11ms | 9ms | -2ms | -18.02
| ChannelStore.GetMembersForUser | avg | 12ms | 10ms | -2ms | -17.27
| PostAcknowledgementStore.GetForPosts | avg | 12ms | 10ms | -2ms | -17.06
| JobStore.Get | avg | 12ms | 10ms | -2ms | -16.14
| ChannelStore.UpdateSidebarCategories | avg | 106ms | 90ms | -16ms | -15.10
| PostStore.Get | avg | 21ms | 18ms | -3ms | -14.59
| ProductNoticesStore.GetViews | avg | 14ms | 12ms | -2ms | -14.32
| PostStore.SetPostReminder | avg | 25ms | 22ms | -3ms | -11.90
| PostStore.SearchPostsForUser | avg | 254ms | 224ms | -30ms | -11.81
| ThreadStore.GetThreadForUser | avg | 17ms | 15ms | -2ms | -11.77
| PostStore.Delete | avg | 52ms | 46ms | -6ms | -11.43
| PreferenceStore.Save | avg | 18ms | 16ms | -2ms | -11.04
| ProductNoticesStore.View | avg | 62ms | 56ms | -6ms | -9.64
| ChannelStore.Save | avg | 32ms | 29ms | -3ms | -9.48
| UserStore.Count | avg | 34ms | 31ms | -3ms | -8.82
| ChannelStore.SaveMember | avg | 57ms | 52ms | -5ms | -8.81
| PostStore.Save | avg | 27ms | 25ms | -2ms | -7.49
| UserStore.AutocompleteUsersInChannel | avg | 87ms | 82ms | -5ms | -5.73
| ChannelStore.GetMemberCount | avg | 38ms | 36ms | -2ms | -5.20
| UserStore.Search | avg | 60ms | 57ms | -3ms | -5.03
| TeamStore.SaveMember | avg | 40ms | 38ms | -2ms | -5.00
| UserStore.GetAllProfilesInChannel | avg | 461ms | 438ms | -23ms | -4.98
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 44ms | 42ms | -2ms | -4.56
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 135ms | 131ms | -4ms | -2.97
| UserStore.Save | avg | 84ms | 82ms | -2ms | -2.38
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 50ms | 0s | -50ms | -101.01
| EmojiStore.Search | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 202ms | 0s | -202ms | -100.00
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 50ms | 5ms | -45ms | -90.91
| JobStore.UpdateStatus | p99 | 158ms | 22ms | -136ms | -85.80
| RetentionPolicyStore.GetCount | p99 | 49ms | 10ms | -39ms | -80.00
| SessionStore.GetSessionsExpired | p99 | 237ms | 48ms | -189ms | -79.92
| DraftStore.Get | p99 | 24ms | 5ms | -19ms | -77.87
| JobStore.UpdateStatusOptimistically | p99 | 158ms | 36ms | -122ms | -76.97
| PostPersistentNotificationStore.DeleteExpired | p99 | 81ms | 22ms | -59ms | -72.84
| UserStore.GetProfilesInChannel | p99 | 815ms | 249ms | -566ms | -69.45
| PostAcknowledgementStore.GetForPost | p99 | 150ms | 49ms | -101ms | -67.39
| UserStore.AnalyticsActiveCount | p99 | 244ms | 99ms | -145ms | -59.43
| PostStore.GetPostReminders | p99 | 217ms | 89ms | -128ms | -58.99
| RetentionPolicyStore.GetAll | p99 | 10ms | 5ms | -5ms | -51.02
| PreferenceStore.DeleteCategoryAndName | p99 | 91ms | 46ms | -45ms | -49.18
| PostPersistentNotificationStore.Get | p99 | 81ms | 42ms | -39ms | -48.15
| ChannelStore.GetSidebarCategory | p99 | 224ms | 127ms | -97ms | -43.27
| PostStore.Update | p99 | 396ms | 242ms | -154ms | -38.91
| ThreadStore.GetThreadUnreadReplyCount | p99 | 148ms | 100ms | -48ms | -32.37
| ProductNoticesStore.View | p99 | 746ms | 519ms | -227ms | -30.44
| PostPriorityStore.GetForPost | p99 | 95ms | 67ms | -28ms | -29.41
| JobStore.Get | p99 | 155ms | 110ms | -45ms | -29.08
| RoleStore.ChannelHigherScopedPermissions | p99 | 67ms | 48ms | -19ms | -28.36
| SessionStore.Save | p99 | 133ms | 98ms | -35ms | -26.30
| ThreadStore.Get | p99 | 98ms | 73ms | -25ms | -25.58
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 73ms | 55ms | -18ms | -24.54
| ChannelStore.Get | p99 | 141ms | 107ms | -34ms | -24.11
| ThreadStore.GetTeamsUnreadForUser | p99 | 127ms | 99ms | -28ms | -22.13
| UserStore.UpdateLastLogin | p99 | 64ms | 50ms | -14ms | -22.03
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 250ms | 198ms | -52ms | -20.84
| PostStore.Save | p99 | 310ms | 249ms | -61ms | -19.66
| ThreadStore.GetThreadsForUser | p99 | 121ms | 98ms | -23ms | -19.06
| UserStore.Count | p99 | 226ms | 183ms | -43ms | -19.03
| PostStore.GetPostIdAfterTime | p99 | 68ms | 56ms | -12ms | -17.60
| StatusStore.Get | p99 | 76ms | 63ms | -13ms | -17.21
| PostAcknowledgementStore.GetForPosts | p99 | 172ms | 143ms | -29ms | -16.89
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 89ms | 74ms | -15ms | -16.85
| FileInfoStore.AttachToPost | p99 | 199ms | 166ms | -33ms | -16.56
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 80ms | 67ms | -13ms | -16.30
| UserStore.IsEmpty | p99 | 40ms | 34ms | -6ms | -14.87
| PostPriorityStore.GetForPosts | p99 | 176ms | 150ms | -26ms | -14.75
| ChannelStore.Autocomplete | p99 | 307ms | 263ms | -44ms | -14.34
| UserStore.Save | p99 | 350ms | 300ms | -50ms | -14.29
| SystemStore.GetByName | p99 | 78ms | 67ms | -11ms | -14.04
| UserStore.GetUnreadCount | p99 | 91ms | 79ms | -12ms | -13.22
| UserTermsOfServiceStore.GetByUser | p99 | 84ms | 73ms | -11ms | -13.17
| SessionStore.Get | p99 | 191ms | 166ms | -25ms | -13.09
| ThreadStore.UpdateMembership | p99 | 85ms | 74ms | -11ms | -12.91
| ThreadStore.MarkAsRead | p99 | 85ms | 74ms | -11ms | -12.89
| PostStore.GetEtag | p99 | 110ms | 96ms | -14ms | -12.72
| ChannelStore.CreateDirectChannel | p99 | 474ms | 414ms | -60ms | -12.66
| UserStore.GetAllProfiles | p99 | 64ms | 56ms | -8ms | -12.44
| PostStore.GetPosts | p99 | 81ms | 71ms | -10ms | -12.40
| ChannelStore.GetMemberLastViewedAt | p99 | 82ms | 72ms | -10ms | -12.21
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 85ms | 75ms | -10ms | -11.80
| AuditStore.Save | p99 | 78ms | 69ms | -9ms | -11.57
| UserStore.Get | p99 | 78ms | 69ms | -9ms | -11.50
| UserStore.GetForLogin | p99 | 79ms | 70ms | -9ms | -11.41
| PluginStore.SetWithOptions | p99 | 101ms | 90ms | -11ms | -10.88
| ChannelStore.UpdateSidebarCategories | p99 | 887ms | 795ms | -92ms | -10.37
| StatusStore.GetByIds | p99 | 98ms | 88ms | -10ms | -10.15
| GroupStore.GetByName | p99 | 80ms | 72ms | -8ms | -10.03
| TeamStore.Get | p99 | 92ms | 83ms | -9ms | -9.79
| PostStore.GetSingle | p99 | 95ms | 86ms | -9ms | -9.52
| StatusStore.UpdateLastActivityAt | p99 | 87ms | 79ms | -8ms | -9.18
| ThreadStore.GetTotalUnreadThreads | p99 | 88ms | 80ms | -8ms | -9.13
| PostPersistentNotificationStore.GetSingle | p99 | 90ms | 82ms | -8ms | -8.92
| TeamStore.GetTeamsByUserId | p99 | 91ms | 83ms | -8ms | -8.82
| ChannelStore.SaveMember | p99 | 491ms | 448ms | -43ms | -8.77
| WebhookStore.GetOutgoingByTeam | p99 | 115ms | 105ms | -10ms | -8.67
| LinkMetadataStore.Get | p99 | 96ms | 88ms | -8ms | -8.33
| ChannelStore.GetAllChannelMembersForUser | p99 | 24ms | 22ms | -2ms | -8.26
| ThreadStore.GetTotalThreads | p99 | 87ms | 80ms | -7ms | -8.02
| PluginStore.Delete | p99 | 50ms | 46ms | -4ms | -8.01
| TeamStore.GetTeamsForUser | p99 | 87ms | 80ms | -7ms | -8.00
| SessionStore.UpdateLastActivityAt | p99 | 88ms | 81ms | -7ms | -8.00
| ChannelStore.IncrementMentionCount | p99 | 88ms | 81ms | -7ms | -7.97
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 89ms | 82ms | -7ms | -7.85
| PostStore.GetPostIdBeforeTime | p99 | 89ms | 82ms | -7ms | -7.85
| PreferenceStore.Save | p99 | 230ms | 212ms | -18ms | -7.81
| ChannelStore.GetPublicChannelsForTeam | p99 | 205ms | 189ms | -16ms | -7.79
| ChannelStore.GetByName | p99 | 90ms | 83ms | -7ms | -7.77
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 91ms | 84ms | -7ms | -7.70
| GroupStore.GetGroups | p99 | 92ms | 85ms | -7ms | -7.65
| PostStore.GetPostsBefore | p99 | 106ms | 98ms | -8ms | -7.54
| PreferenceStore.GetAll | p99 | 95ms | 88ms | -7ms | -7.38
| EmojiStore.GetByName | p99 | 95ms | 88ms | -7ms | -7.37
| PostStore.Get | p99 | 227ms | 211ms | -16ms | -7.06
| ThreadStore.GetTotalUnreadMentions | p99 | 88ms | 82ms | -6ms | -6.81
| ChannelStore.UpdateLastViewedAt | p99 | 89ms | 83ms | -6ms | -6.76
| PostStore.SetPostReminder | p99 | 232ms | 217ms | -15ms | -6.47
| PostStore.GetPostsAfter | p99 | 94ms | 88ms | -6ms | -6.41
| ThreadStore.GetThreadForUser | p99 | 190ms | 178ms | -12ms | -6.31
| UserStore.GetProfileByIds | p99 | 100ms | 94ms | -6ms | -6.02
| UserStore.UpdateUpdateAt | p99 | 68ms | 64ms | -4ms | -5.92
| TeamStore.SaveMember | p99 | 257ms | 242ms | -15ms | -5.84
| TeamStore.GetAllPage | p99 | 87ms | 82ms | -5ms | -5.72
| ChannelStore.GetFileCount | p99 | 93ms | 88ms | -5ms | -5.35
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 94ms | 89ms | -5ms | -5.29
| ChannelStore.GetGuestCount | p99 | 95ms | 90ms | -5ms | -5.27
| ChannelStore.GetPinnedPostCount | p99 | 95ms | 90ms | -5ms | -5.24
| ChannelStore.CreateInitialSidebarCategories | p99 | 460ms | 438ms | -22ms | -4.79
| ChannelStore.GetMemberCount | p99 | 229ms | 219ms | -10ms | -4.36
| ThreadStore.MarkAllAsReadByChannels | p99 | 92ms | 88ms | -4ms | -4.33
| ChannelStore.GetMemberForPost | p99 | 96ms | 92ms | -4ms | -4.18
| PreferenceStore.Get | p99 | 98ms | 94ms | -4ms | -4.09
| PostStore.GetPostsByThread | p99 | 100ms | 96ms | -4ms | -4.02
| PostStore.GetPostsSince | p99 | 218ms | 210ms | -8ms | -3.68
| PostStore.SearchPostsForUser | p99 | 2.497s | 2.408s | -89ms | -3.56
| ThreadStore.MaintainMembership | p99 | 214ms | 207ms | -7ms | -3.27
| ChannelStore.GetChannelUnread | p99 | 96ms | 93ms | -3ms | -3.14
| FileInfoStore.Get | p99 | 97ms | 94ms | -3ms | -3.08
| UserStore.GetProfilesByUsernames | p99 | 98ms | 95ms | -3ms | -3.05
| ChannelStore.GetChannels | p99 | 98ms | 95ms | -3ms | -3.05
| UserStore.GetAllProfilesInChannel | p99 | 2.332s | 2.261s | -71ms | -3.04
| FileInfoStore.GetForPost | p99 | 90ms | 88ms | -2ms | -2.22
| ChannelStore.GetChannelsByUser | p99 | 96ms | 94ms | -2ms | -2.09
| ChannelStore.GetMembersForUser | p99 | 98ms | 96ms | -2ms | -2.03
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 248ms | 243ms | -5ms | -2.02
| PostStore.GetPostReminderMetadata | p99 | 184ms | 181ms | -3ms | -1.63
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 10ms | 10ms | 5511.84
| getPrevTrialLicense | avg | 5ms | 9ms | 4ms | 85.99
| getChannelMembers | avg | 6ms | 11ms | 5ms | 84.42
| getChannelMembersForUser | avg | 20ms | 36ms | 16ms | 81.86
| searchGroupChannels | avg | 14ms | 20ms | 6ms | 43.96
| getCategoriesForTeamForUser | avg | 32ms | 45ms | 13ms | 41.07
| getFilteredUsersStats | avg | 36ms | 48ms | 12ms | 33.34
| getLicenseSelfServeStatus | avg | 70ms | 91ms | 21ms | 30.15
| getProductNotices | avg | 10ms | 12ms | 2ms | 19.25
| autocompleteChannelsForTeamForSearch | avg | 103ms | 119ms | 16ms | 15.53
| createChannel | avg | 27ms | 30ms | 3ms | 11.10
| getAnalytics | avg | 63ms | 70ms | 7ms | 11.09
| removeUserCustomStatus | avg | 285ms | 304ms | 19ms | 6.66
| createGroupChannel | avg | 690ms | 705ms | 15ms | 2.17
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 5ms | 235ms | 230ms | 4646.46
| autocompleteChannelsForTeamForSearch | p99 | 346ms | 3.595s | 3.249s | 940.05
| getLicenseSelfServeStatus | p99 | 100ms | 244ms | 144ms | 144.72
| getChannelMembers | p99 | 24ms | 49ms | 25ms | 103.74
| getPrevTrialLicense | p99 | 24ms | 49ms | 25ms | 103.41
| getChannelMembersForUser | p99 | 49ms | 99ms | 50ms | 102.04
| createChannel | p99 | 50ms | 97ms | 47ms | 94.83
| getJobsByType | p99 | 48ms | 93ms | 45ms | 94.23
| removeUserCustomStatus | p99 | 1.518s | 2.173s | 655ms | 43.16
| searchGroupChannels | p99 | 132ms | 140ms | 8ms | 6.07
| updateCategoriesForTeamForUser | p99 | 1.825s | 1.885s | 60ms | 3.29
| addChannelMember | p99 | 2.312s | 2.372s | 60ms | 2.60
| unfollowThreadByUser | p99 | 420ms | 430ms | 10ms | 2.38
| getAnalytics | p99 | 240ms | 243ms | 3ms | 1.25
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 15ms | 0s | -15ms | -101.78
| autocompleteEmojis | avg | 40ms | 0s | -40ms | -101.19
| channelMemberCountsByGroup | avg | 12ms | 0s | -12ms | -101.01
| createCategoryForTeamForUser | avg | 50ms | 0s | -50ms | -100.86
| getPluginStatuses | avg | 30ms | 0s | -30ms | -98.99
| upsertDraft | avg | 56ms | 3ms | -53ms | -94.79
| getGroupsAssociatedToChannelsByTeam | avg | 26ms | 2ms | -24ms | -93.35
| getRolesByNames | avg | 5ms | 1ms | -4ms | -78.83
| getGroups | avg | 17ms | 4ms | -13ms | -75.40
| patchPost | avg | 191ms | 97ms | -94ms | -49.21
| deleteDraft | avg | 5ms | 3ms | -2ms | -41.20
| followThreadByUser | avg | 56ms | 33ms | -23ms | -40.91
| getJobsByType | avg | 9ms | 7ms | -2ms | -22.56
| getTeamMember | avg | 10ms | 8ms | -2ms | -20.51
| deletePost | avg | 85ms | 69ms | -16ms | -18.93
| setPostReminder | avg | 69ms | 56ms | -13ms | -18.84
| updatePreferences | avg | 32ms | 26ms | -6ms | -18.83
| getChannelsForUser | avg | 12ms | 10ms | -2ms | -17.29
| updateCategoriesForTeamForUser | avg | 157ms | 130ms | -27ms | -17.18
| getChannelMember | avg | 20ms | 17ms | -3ms | -15.15
| getPostThread | avg | 54ms | 46ms | -8ms | -14.88
| getThreadsForUser | avg | 14ms | 12ms | -2ms | -14.78
| getChannel | avg | 22ms | 19ms | -3ms | -13.67
| getUsers | avg | 15ms | 13ms | -2ms | -13.22
| getClientConfig | avg | 16ms | 14ms | -2ms | -12.74
| login | avg | 159ms | 141ms | -18ms | -11.32
| updateReadStateThreadByUser | avg | 129ms | 115ms | -14ms | -10.89
| searchPostsInTeam | avg | 277ms | 247ms | -30ms | -10.82
| createDirectChannel | avg | 446ms | 402ms | -44ms | -9.87
| saveReaction | avg | 35ms | 32ms | -3ms | -8.54
| viewChannel | avg | 35ms | 32ms | -3ms | -8.49
| getPostsForChannel | avg | 92ms | 85ms | -7ms | -7.58
| getPostsForChannelAroundLastUnread | avg | 43ms | 40ms | -3ms | -6.99
| autocompleteUsers | avg | 73ms | 68ms | -5ms | -6.85
| getFileThumbnail | avg | 61ms | 57ms | -4ms | -6.61
| createPost | avg | 827ms | 775ms | -52ms | -6.29
| getProfileImage | avg | 97ms | 91ms | -6ms | -6.16
| searchUsers | avg | 63ms | 60ms | -3ms | -4.80
| getFilePreview | avg | 72ms | 69ms | -3ms | -4.18
| createUser | avg | 135ms | 130ms | -5ms | -3.71
| logout | avg | 141ms | 137ms | -4ms | -2.83
| addTeamMember | avg | 1.307s | 1.273s | -34ms | -2.60
| uploadFileStream | avg | 495ms | 489ms | -6ms | -1.21
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 50ms | 0s | -50ms | -101.01
| autocompleteEmojis | p99 | 50ms | 0s | -50ms | -100.50
| getPluginStatuses | p99 | 50ms | 0s | -50ms | -100.45
| createCategoryForTeamForUser | p99 | 99ms | 0s | -99ms | -100.00
| channelMemberCountsByGroup | p99 | 202ms | 0s | -202ms | -100.00
| upsertDraft | p99 | 100ms | 5ms | -95ms | -95.48
| getGroupsAssociatedToChannelsByTeam | p99 | 50ms | 5ms | -45ms | -90.45
| getGroups | p99 | 50ms | 10ms | -40ms | -80.81
| followThreadByUser | p99 | 900ms | 234ms | -666ms | -74.00
| patchPost | p99 | 2.38s | 840ms | -1.54s | -64.71
| deleteDraft | p99 | 24ms | 10ms | -14ms | -57.73
| setPostReminder | p99 | 880ms | 445ms | -435ms | -49.43
| logout | p99 | 855ms | 480ms | -375ms | -43.86
| createGroupChannel | p99 | 4.194s | 2.484s | -1.71s | -40.78
| getTeamMember | p99 | 138ms | 92ms | -46ms | -33.30
| updatePreferences | p99 | 363ms | 247ms | -116ms | -31.99
| searchPostsInTeam | p99 | 3.579s | 2.457s | -1.122s | -31.35
| login | p99 | 1.32s | 964ms | -356ms | -26.97
| getThreadsForUser | p99 | 143ms | 111ms | -32ms | -22.34
| createDirectChannel | p99 | 2.374s | 1.962s | -412ms | -17.35
| createUser | p99 | 796ms | 661ms | -135ms | -16.97
| searchAllChannels | p99 | 315ms | 263ms | -52ms | -16.53
| getFileThumbnail | p99 | 363ms | 308ms | -55ms | -15.16
| getChannelsForTeamForUser | p99 | 115ms | 99ms | -16ms | -13.90
| getUsersByIds | p99 | 37ms | 32ms | -5ms | -13.60
| getChannel | p99 | 212ms | 186ms | -26ms | -12.24
| getTeamsUnreadForUser | p99 | 198ms | 174ms | -24ms | -12.10
| viewChannel | p99 | 403ms | 359ms | -44ms | -10.92
| getUsers | p99 | 232ms | 207ms | -25ms | -10.79
| getPublicChannelsForTeam | p99 | 210ms | 189ms | -21ms | -9.98
| addTeamMember | p99 | 8.394s | 7.601s | -793ms | -9.45
| getFilePreview | p99 | 403ms | 366ms | -37ms | -9.17
| getTeamsForUser | p99 | 92ms | 84ms | -8ms | -8.70
| getClientConfig | p99 | 227ms | 209ms | -18ms | -7.94
| getPostsForChannelAroundLastUnread | p99 | 468ms | 434ms | -34ms | -7.27
| getPreferences | p99 | 98ms | 91ms | -7ms | -7.14
| updateReadStateThreadByUser | p99 | 917ms | 853ms | -64ms | -6.98
| getChannelStats | p99 | 189ms | 177ms | -12ms | -6.35
| getPostThread | p99 | 478ms | 448ms | -30ms | -6.27
| getPostsForChannel | p99 | 963ms | 903ms | -60ms | -6.23
| getChannelMember | p99 | 233ms | 219ms | -14ms | -6.02
| getAllTeams | p99 | 97ms | 93ms | -4ms | -4.10
| getUsersByNames | p99 | 100ms | 96ms | -4ms | -4.01
| getTeamMembersForUser | p99 | 100ms | 97ms | -3ms | -3.01
| autocompleteUsers | p99 | 405ms | 393ms | -12ms | -2.96
| getChannelMembersForTeamForUser | p99 | 102ms | 99ms | -3ms | -2.95
| getChannelUnread | p99 | 99ms | 97ms | -2ms | -2.02
| getUser | p99 | 214ms | 210ms | -4ms | -1.87
| createPost | p99 | 4.686s | 4.6s | -86ms | -1.84
| getProfileImage | p99 | 488ms | 481ms | -7ms | -1.44
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 6ms | -1ms | -15.303
| |  P99| 78ms| 69ms | -9ms | -11.569
| BotStore.Get |  Avg| 9ms| 6ms | -3ms | -32.341
| |  P99| 44ms| 47ms | 3ms | 6.818
| BotStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 135ms| 131ms | -4ms | -2.974
| |  P99| 479ms| 477ms | -2ms | -0.417
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 5ms | -1ms | -17.813
| |  P99| 73ms| 55ms | -18ms | -24.543
| ChannelStore.AnalyticsTypeCount |  Avg| 27ms| 21ms | -6ms | -22.459
| |  P99| 94ms| 97ms | 3ms | 3.187
| ChannelStore.Autocomplete |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 307ms| 263ms | -44ms | -14.343
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 103ms| 119ms | 16ms | 15.545
| |  P99| 346ms| 3.595s | 3.249s | 940.053
| ChannelStore.CreateDirectChannel |  Avg| 64ms| 52ms | -12ms | -18.896
| |  P99| 474ms| 414ms | -60ms | -12.665
| ChannelStore.CreateInitialSidebarCategories |  Avg| 37ms| 55ms | 18ms | 48.746
| |  P99| 460ms| 438ms | -22ms | -4.787
| ChannelStore.CreateSidebarCategory |  Avg| 35ms| 0s | -35ms | -100.692
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.Get |  Avg| 12ms| 11ms | -1ms | -8.344
| |  P99| 141ms| 107ms | -34ms | -24.106
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 36ms| 29ms | -7ms | -19.451
| |  P99| 250ms| 198ms | -52ms | -20.838
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.257
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 44ms| 42ms | -2ms | -4.563
| |  P99| 248ms| 243ms | -5ms | -2.020
| ChannelStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 83ms | -7ms | -7.774
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 4ms | 3ms | 226.698
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 11ms| 10ms | -1ms | -9.501
| |  P99| 96ms| 93ms | -3ms | -3.141
| ChannelStore.GetChannels |  Avg| 10ms| 9ms | -1ms | -9.678
| |  P99| 98ms| 95ms | -3ms | -3.047
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 10ms | -1ms | -8.876
| |  P99| 96ms| 94ms | -2ms | -2.089
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 8ms | -1ms | -11.185
| |  P99| 94ms| 89ms | -5ms | -5.292
| ChannelStore.GetFileCount |  Avg| 10ms| 9ms | -1ms | -9.541
| |  P99| 93ms| 88ms | -5ms | -5.348
| ChannelStore.GetGuestCount |  Avg| 9ms| 8ms | -1ms | -11.380
| |  P99| 95ms| 90ms | -5ms | -5.270
| ChannelStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.072
| ChannelStore.GetMemberCount |  Avg| 38ms| 36ms | -2ms | -5.200
| |  P99| 229ms| 219ms | -10ms | -4.363
| ChannelStore.GetMemberCountsByGroup |  Avg| 11ms| 0s | -11ms | -99.599
| |  P99| 202ms| 0s | -202ms | -99.998
| ChannelStore.GetMemberForPost |  Avg| 13ms| 12ms | -1ms | -7.724
| |  P99| 96ms| 92ms | -4ms | -4.180
| ChannelStore.GetMemberLastViewedAt |  Avg| 6ms| 5ms | -1ms | -16.590
| |  P99| 82ms| 72ms | -10ms | -12.212
| ChannelStore.GetMembers |  Avg| 5ms| 10ms | 5ms | 95.046
| |  P99| 24ms| 49ms | 25ms | 103.737
| ChannelStore.GetMembersForUser |  Avg| 12ms| 10ms | -2ms | -17.269
| |  P99| 98ms| 96ms | -2ms | -2.034
| ChannelStore.GetMembersForUserWithPagination |  Avg| 23ms| 39ms | 16ms | 69.046
| |  P99| 89ms| 235ms | 146ms | 164.971
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 8ms | -1ms | -10.841
| |  P99| 95ms| 90ms | -5ms | -5.239
| ChannelStore.GetPublicChannelsForTeam |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 205ms| 189ms | -16ms | -7.791
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 31ms| 45ms | 14ms | 44.824
| |  P99| 235ms| 236ms | 1ms | 0.426
| ChannelStore.GetSidebarCategory |  Avg| 22ms| 18ms | -4ms | -18.339
| |  P99| 224ms| 127ms | -97ms | -43.265
| ChannelStore.GetTeamChannels |  Avg| 27ms| 30ms | 3ms | 11.169
| |  P99| 49ms| 97ms | 48ms | 97.057
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 88ms| 81ms | -7ms | -7.975
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 32ms| 29ms | -3ms | -9.484
| |  P99| 245ms| 346ms | 101ms | 41.166
| ChannelStore.SaveMember |  Avg| 57ms| 52ms | -5ms | -8.808
| |  P99| 491ms| 448ms | -43ms | -8.766
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 20ms | 6ms | 44.307
| |  P99| 128ms| 134ms | 6ms | 4.700
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 8ms | -1ms | -11.555
| |  P99| 89ms| 83ms | -6ms | -6.760
| ChannelStore.UpdateSidebarCategories |  Avg| 106ms| 90ms | -16ms | -15.100
| |  P99| 887ms| 795ms | -92ms | -10.366
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 6ms| 5ms | -1ms | -15.834
| |  P99| 85ms| 75ms | -10ms | -11.796
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 7ms| 8ms | 1ms | 14.578
| |  P99| 70ms| 96ms | 26ms | 36.879
| CommandWebhookStore.Cleanup |  Avg| 2ms| 5ms | 3ms | 194.924
| |  P99| 5ms| 10ms | 5ms | 101.002
| ComplianceStore.MessageExport |  Avg| 12ms| 13ms | 1ms | 8.534
| |  P99| 97ms| 98ms | 1ms | 1.031
| DraftStore.Get |  Avg| 5ms| 1ms | -4ms | -84.554
| |  P99| 24ms| 5ms | -19ms | -77.869
| DraftStore.GetDraftsForUser |  Avg| 4ms| 27ms | 23ms | 605.846
| |  P99| 10ms| 50ms | 40ms | 404.040
| EmojiStore.GetByName |  Avg| 9ms| 8ms | -1ms | -11.713
| |  P99| 95ms| 88ms | -7ms | -7.371
| EmojiStore.GetMultipleByName |  Avg| 19ms| 20ms | 1ms | 5.227
| |  P99| 98ms| 98ms | 0s | 0.000
| EmojiStore.Search |  Avg| 39ms| 0s | -39ms | -98.772
| |  P99| 50ms| 0s | -50ms | -100.503
| FileInfoStore.AttachToPost |  Avg| 14ms| 13ms | -1ms | -6.997
| |  P99| 199ms| 166ms | -33ms | -16.558
| FileInfoStore.Get |  Avg| 10ms| 9ms | -1ms | -10.379
| |  P99| 97ms| 94ms | -3ms | -3.082
| FileInfoStore.GetForPost |  Avg| 9ms| 8ms | -1ms | -11.503
| |  P99| 90ms| 88ms | -2ms | -2.218
| FileInfoStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 94ms| 95ms | 1ms | 1.063
| FileInfoStore.SetContent |  Avg| 16ms| 17ms | 1ms | 6.135
| |  P99| 183ms| 187ms | 4ms | 2.182
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 80ms| 67ms | -13ms | -16.305
| GroupStore.GetByName |  Avg| 6ms| 5ms | -1ms | -17.326
| |  P99| 80ms| 72ms | -8ms | -10.031
| GroupStore.GetGroups |  Avg| 9ms| 8ms | -1ms | -11.285
| |  P99| 92ms| 85ms | -7ms | -7.648
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 16ms| 2ms | -14ms | -87.155
| |  P99| 50ms| 5ms | -45ms | -90.909
| JobStore.Get |  Avg| 12ms| 10ms | -2ms | -16.145
| |  P99| 155ms| 110ms | -45ms | -29.079
| JobStore.GetAllByStatus |  Avg| 10ms| 9ms | -1ms | -9.819
| |  P99| 95ms| 105ms | 10ms | 10.566
| JobStore.GetAllByTypePage |  Avg| 9ms| 8ms | -1ms | -11.503
| |  P99| 48ms| 92ms | 44ms | 92.138
| JobStore.GetCountByStatusAndType |  Avg| 7ms| 6ms | -1ms | -14.914
| |  P99| 46ms| 87ms | 41ms | 88.172
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 77ms | 31ms | 67.118
| JobStore.Save |  Avg| 5ms| 6ms | 1ms | 21.349
| |  P99| 42ms| 73ms | 31ms | 73.156
| JobStore.UpdateOptimistically |  Avg| 8ms| 7ms | -1ms | -11.914
| |  P99| 81ms| 80ms | -1ms | -1.233
| JobStore.UpdateStatus |  Avg| 11ms| 3ms | -8ms | -71.841
| |  P99| 158ms| 22ms | -136ms | -85.804
| JobStore.UpdateStatusOptimistically |  Avg| 13ms| 4ms | -9ms | -69.670
| |  P99| 158ms| 36ms | -122ms | -76.972
| LicenseStore.GetAll |  Avg| 4ms| 7ms | 3ms | 80.201
| |  P99| 23ms| 48ms | 25ms | 109.171
| LinkMetadataStore.Get |  Avg| 9ms| 8ms | -1ms | -10.965
| |  P99| 96ms| 88ms | -8ms | -8.331
| LinkMetadataStore.Save |  Avg| 10ms| 6ms | -4ms | -41.905
| |  P99| 99ms| 138ms | 39ms | 39.417
| PluginStore.Delete |  Avg| 4ms| 3ms | -1ms | -25.302
| |  P99| 50ms| 46ms | -4ms | -8.014
| PluginStore.Get |  Avg| 3ms| 9ms | 6ms | 236.980
| |  P99| 9ms| 49ms | 40ms | 421.053
| PluginStore.List |  Avg| 9ms| 6ms | -3ms | -34.459
| |  P99| 74ms| 74ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 9ms| 8ms | -1ms | -10.903
| |  P99| 101ms| 90ms | -11ms | -10.882
| PostAcknowledgementStore.GetForPost |  Avg| 8ms| 6ms | -2ms | -23.729
| |  P99| 150ms| 49ms | -101ms | -67.392
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 10ms | -2ms | -17.064
| |  P99| 172ms| 143ms | -29ms | -16.892
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 2ms | -3ms | -61.077
| |  P99| 81ms| 22ms | -59ms | -72.840
| PostPersistentNotificationStore.Get |  Avg| 7ms| 3ms | -4ms | -53.884
| |  P99| 81ms| 42ms | -39ms | -48.148
| PostPersistentNotificationStore.GetSingle |  Avg| 8ms| 7ms | -1ms | -12.999
| |  P99| 90ms| 82ms | -8ms | -8.917
| PostPriorityStore.GetForPost |  Avg| 9ms| 6ms | -3ms | -34.904
| |  P99| 95ms| 67ms | -28ms | -29.408
| PostPriorityStore.GetForPosts |  Avg| 12ms| 11ms | -1ms | -8.110
| |  P99| 176ms| 150ms | -26ms | -14.754
| PostStore.AnalyticsPostCount |  Avg| 237ms| 398ms | 161ms | 67.958
| |  P99| 495ms| 990ms | 495ms | 100.000
| PostStore.Delete |  Avg| 52ms| 46ms | -6ms | -11.431
| |  P99| 457ms| 455ms | -2ms | -0.437
| PostStore.Get |  Avg| 21ms| 18ms | -3ms | -14.592
| |  P99| 227ms| 211ms | -16ms | -7.059
| PostStore.GetEtag |  Avg| 10ms| 9ms | -1ms | -9.527
| |  P99| 110ms| 96ms | -14ms | -12.721
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 4ms | -1ms | -22.156
| |  P99| 68ms| 56ms | -12ms | -17.605
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 6ms | -1ms | -14.624
| |  P99| 89ms| 82ms | -7ms | -7.852
| PostStore.GetPostReminderMetadata |  Avg| 14ms| 10ms | -4ms | -29.175
| |  P99| 184ms| 181ms | -3ms | -1.630
| PostStore.GetPostReminders |  Avg| 18ms| 7ms | -11ms | -61.284
| |  P99| 217ms| 89ms | -128ms | -58.986
| PostStore.GetPosts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 71ms | -10ms | -12.403
| PostStore.GetPostsAfter |  Avg| 11ms| 9ms | -2ms | -18.017
| |  P99| 94ms| 88ms | -6ms | -6.415
| PostStore.GetPostsBefore |  Avg| 12ms| 11ms | -1ms | -8.020
| |  P99| 106ms| 98ms | -8ms | -7.539
| PostStore.GetPostsByThread |  Avg| 15ms| 14ms | -1ms | -6.894
| |  P99| 100ms| 96ms | -4ms | -4.018
| PostStore.GetPostsSince |  Avg| 27ms| 26ms | -1ms | -3.637
| |  P99| 218ms| 210ms | -8ms | -3.675
| PostStore.GetSingle |  Avg| 9ms| 8ms | -1ms | -11.305
| |  P99| 95ms| 86ms | -9ms | -9.515
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 27ms| 25ms | -2ms | -7.490
| |  P99| 310ms| 249ms | -61ms | -19.657
| PostStore.SearchPostsForUser |  Avg| 254ms| 224ms | -30ms | -11.813
| |  P99| 2.497s| 2.408s | -89ms | -3.564
| PostStore.SetPostReminder |  Avg| 25ms| 22ms | -3ms | -11.898
| |  P99| 232ms| 217ms | -15ms | -6.466
| PostStore.Update |  Avg| 31ms| 23ms | -8ms | -26.093
| |  P99| 396ms| 242ms | -154ms | -38.905
| PreferenceStore.DeleteCategoryAndName |  Avg| 14ms| 7ms | -7ms | -49.698
| |  P99| 91ms| 46ms | -45ms | -49.181
| PreferenceStore.Get |  Avg| 10ms| 9ms | -1ms | -10.040
| |  P99| 98ms| 94ms | -4ms | -4.091
| PreferenceStore.GetAll |  Avg| 8ms| 7ms | -1ms | -11.920
| |  P99| 95ms| 88ms | -7ms | -7.384
| PreferenceStore.Save |  Avg| 18ms| 16ms | -2ms | -11.039
| |  P99| 230ms| 212ms | -18ms | -7.813
| ProductNoticesStore.ClearOldNotices |  Avg| 35ms| 37ms | 2ms | 5.686
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 14ms| 12ms | -2ms | -14.322
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 62ms| 56ms | -6ms | -9.637
| |  P99| 746ms| 519ms | -227ms | -30.442
| ReactionStore.GetForPost |  Avg| 7ms| 8ms | 1ms | 13.371
| |  P99| 75ms| 76ms | 1ms | 1.334
| RetentionPolicyStore.GetAll |  Avg| 4ms| 2ms | -2ms | -49.491
| |  P99| 10ms| 5ms | -5ms | -51.020
| RetentionPolicyStore.GetCount |  Avg| 11ms| 3ms | -8ms | -75.620
| |  P99| 49ms| 10ms | -39ms | -80.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 67ms| 48ms | -19ms | -28.358
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 13ms| 12ms | -1ms | -7.668
| |  P99| 191ms| 166ms | -25ms | -13.088
| SessionStore.GetSessionsExpired |  Avg| 28ms| 4ms | -24ms | -84.924
| |  P99| 237ms| 48ms | -189ms | -79.915
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 7ms | -1ms | -12.244
| |  P99| 89ms| 74ms | -15ms | -16.849
| SessionStore.Remove |  Avg| 9ms| 11ms | 2ms | 22.394
| |  P99| 85ms| 93ms | 8ms | 9.357
| SessionStore.Save |  Avg| 12ms| 11ms | -1ms | -8.076
| |  P99| 133ms| 98ms | -35ms | -26.301
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 81ms | -7ms | -7.997
| StatusStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 76ms| 63ms | -13ms | -17.211
| StatusStore.GetByIds |  Avg| 12ms| 9ms | -3ms | -24.397
| |  P99| 98ms| 88ms | -10ms | -10.152
| StatusStore.SaveOrUpdate |  Avg| 52ms| 111ms | 59ms | 114.270
| |  P99| 870ms| 981ms | 111ms | 12.763
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 49ms| 89ms | 40ms | 81.800
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 7ms | -1ms | -13.231
| |  P99| 87ms| 79ms | -8ms | -9.176
| SystemStore.GetByName |  Avg| 5ms| 4ms | -1ms | -20.707
| |  P99| 78ms| 67ms | -11ms | -14.036
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 14ms | 8ms | 128.943
| |  P99| 24ms| 96ms | 72ms | 300.641
| TeamStore.Get |  Avg| 8ms| 7ms | -1ms | -12.452
| |  P99| 92ms| 83ms | -9ms | -9.793
| TeamStore.GetAllPage |  Avg| 7ms| 6ms | -1ms | -14.659
| |  P99| 87ms| 82ms | -5ms | -5.717
| TeamStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 74ms | 5ms | 7.295
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 7ms | -1ms | -12.665
| |  P99| 91ms| 84ms | -7ms | -7.695
| TeamStore.GetMember |  Avg| 2ms| 3ms | 1ms | 40.659
| |  P99| 35ms| 39ms | 4ms | 11.426
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 6ms | -1ms | -13.720
| |  P99| 91ms| 83ms | -8ms | -8.818
| TeamStore.GetTeamsForUser |  Avg| 8ms| 7ms | -1ms | -13.330
| |  P99| 87ms| 80ms | -7ms | -8.001
| TeamStore.SaveMember |  Avg| 40ms| 38ms | -2ms | -4.999
| |  P99| 257ms| 242ms | -15ms | -5.841
| ThreadStore.Get |  Avg| 9ms| 8ms | -1ms | -10.896
| |  P99| 98ms| 73ms | -25ms | -25.575
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.099
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 10ms | -1ms | -8.781
| |  P99| 127ms| 99ms | -28ms | -22.129
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.165
| ThreadStore.GetThreadForUser |  Avg| 17ms| 15ms | -2ms | -11.766
| |  P99| 190ms| 178ms | -12ms | -6.313
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 17ms| 16ms | -1ms | -5.937
| |  P99| 148ms| 100ms | -48ms | -32.374
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 12ms | -1ms | -7.579
| |  P99| 121ms| 98ms | -23ms | -19.060
| ThreadStore.GetTotalThreads |  Avg| 8ms| 7ms | -1ms | -13.060
| |  P99| 87ms| 80ms | -7ms | -8.017
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 7ms | -1ms | -12.739
| |  P99| 88ms| 82ms | -6ms | -6.808
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 7ms | -1ms | -12.906
| |  P99| 88ms| 80ms | -8ms | -9.133
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 7ms | -1ms | -12.385
| |  P99| 89ms| 82ms | -7ms | -7.854
| ThreadStore.MaintainMembership |  Avg| 16ms| 15ms | -1ms | -6.369
| |  P99| 214ms| 207ms | -7ms | -3.273
| ThreadStore.MarkAllAsReadByChannels |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 88ms | -4ms | -4.335
| ThreadStore.MarkAllAsReadByTeam |  Avg| 15ms| 0s | -15ms | -102.559
| |  P99| 50ms| 0s | -50ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 8ms| 7ms | -1ms | -12.463
| |  P99| 85ms| 74ms | -11ms | -12.895
| ThreadStore.UpdateMembership |  Avg| 8ms| 7ms | -1ms | -12.996
| |  P99| 85ms| 74ms | -11ms | -12.908
| TokenStore.Cleanup |  Avg| 1ms| 16ms | 15ms | 1270.154
| |  P99| 5ms| 25ms | 20ms | 404.016
| UserAccessTokenStore.GetByToken |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 44ms| 85ms | 41ms | 92.787
| UserStore.AnalyticsActiveCount |  Avg| 64ms| 44ms | -20ms | -31.377
| |  P99| 244ms| 99ms | -145ms | -59.427
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 4ms| 6ms | 2ms | 52.687
| |  P99| 24ms| 49ms | 25ms | 103.094
| UserStore.AutocompleteUsersInChannel |  Avg| 87ms| 82ms | -5ms | -5.732
| |  P99| 440ms| 436ms | -4ms | -0.909
| UserStore.Count |  Avg| 34ms| 31ms | -3ms | -8.815
| |  P99| 226ms| 183ms | -43ms | -19.027
| UserStore.Get |  Avg| 6ms| 5ms | -1ms | -17.480
| |  P99| 78ms| 69ms | -9ms | -11.499
| UserStore.GetAllProfiles |  Avg| 7ms| 6ms | -1ms | -14.372
| |  P99| 64ms| 56ms | -8ms | -12.437
| UserStore.GetAllProfilesInChannel |  Avg| 461ms| 438ms | -23ms | -4.984
| |  P99| 2.332s| 2.261s | -71ms | -3.044
| UserStore.GetByUsername |  Avg| 8ms| 11ms | 3ms | 37.536
| |  P99| 60ms| 162ms | 102ms | 170.950
| UserStore.GetForLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 79ms| 70ms | -9ms | -11.408
| UserStore.GetMany |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 47ms | 1ms | 2.162
| UserStore.GetProfileByIds |  Avg| 10ms| 9ms | -1ms | -10.017
| |  P99| 100ms| 94ms | -6ms | -6.016
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 9ms | -1ms | -9.543
| |  P99| 98ms| 95ms | -3ms | -3.048
| UserStore.GetProfilesInChannel |  Avg| 272ms| 58ms | -214ms | -78.795
| |  P99| 815ms| 249ms | -566ms | -69.448
| UserStore.GetUnreadCount |  Avg| 9ms| 8ms | -1ms | -11.379
| |  P99| 91ms| 79ms | -12ms | -13.216
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 34ms | -6ms | -14.869
| UserStore.Save |  Avg| 84ms| 82ms | -2ms | -2.383
| |  P99| 350ms| 300ms | -50ms | -14.287
| UserStore.Search |  Avg| 60ms| 57ms | -3ms | -5.028
| |  P99| 246ms| 244ms | -2ms | -0.814
| UserStore.Update |  Avg| 16ms| 19ms | 3ms | 18.770
| |  P99| 210ms| 217ms | 7ms | 3.331
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 75ms| 74ms | -1ms | -1.329
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 64ms| 50ms | -14ms | -22.026
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 64ms | -4ms | -5.920
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 5ms | -1ms | -16.054
| |  P99| 84ms| 73ms | -11ms | -13.173
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 115ms| 105ms | -10ms | -8.670
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 433ms| 437ms | 4ms | 0.924
| | P99| 2.312s| 2.372s | 60ms | 2.595
| addTeamMember | Avg| 1.307s| 1.273s | -34ms | -2.602
| | P99| 8.394s| 7.601s | -793ms | -9.447
| autocompleteChannelsForTeamForSearch | Avg| 103ms| 119ms | 16ms | 15.533
| | P99| 346ms| 3.595s | 3.249s | 940.053
| autocompleteEmojis | Avg| 40ms| 0s | -40ms | -101.187
| | P99| 50ms| 0s | -50ms | -100.503
| autocompleteUsers | Avg| 73ms| 68ms | -5ms | -6.850
| | P99| 405ms| 393ms | -12ms | -2.964
| channelMemberCountsByGroup | Avg| 12ms| 0s | -12ms | -101.008
| | P99| 202ms| 0s | -202ms | -99.998
| createCategoryForTeamForUser | Avg| 50ms| 0s | -50ms | -100.857
| | P99| 99ms| 0s | -99ms | -100.000
| createChannel | Avg| 27ms| 30ms | 3ms | 11.104
| | P99| 50ms| 97ms | 47ms | 94.826
| createDirectChannel | Avg| 446ms| 402ms | -44ms | -9.867
| | P99| 2.374s| 1.962s | -412ms | -17.355
| createGroupChannel | Avg| 690ms| 705ms | 15ms | 2.174
| | P99| 4.194s| 2.484s | -1.71s | -40.775
| createPost | Avg| 827ms| 775ms | -52ms | -6.288
| | P99| 4.686s| 4.6s | -86ms | -1.835
| createUser | Avg| 135ms| 130ms | -5ms | -3.713
| | P99| 796ms| 661ms | -135ms | -16.967
| deleteDraft | Avg| 5ms| 3ms | -2ms | -41.195
| | P99| 24ms| 10ms | -14ms | -57.732
| deletePost | Avg| 85ms| 69ms | -16ms | -18.933
| | P99| 457ms| 455ms | -2ms | -0.437
| followThreadByUser | Avg| 56ms| 33ms | -23ms | -40.912
| | P99| 900ms| 234ms | -666ms | -73.999
| getAllTeams | Avg| 8ms| 7ms | -1ms | -12.103
| | P99| 97ms| 93ms | -4ms | -4.103
| getAnalytics | Avg| 63ms| 70ms | 7ms | 11.087
| | P99| 240ms| 243ms | 3ms | 1.250
| getCategoriesForTeamForUser | Avg| 32ms| 45ms | 13ms | 41.065
| | P99| 236ms| 238ms | 2ms | 0.846
| getChannel | Avg| 22ms| 19ms | -3ms | -13.667
| | P99| 212ms| 186ms | -26ms | -12.235
| getChannelMember | Avg| 20ms| 17ms | -3ms | -15.150
| | P99| 233ms| 219ms | -14ms | -6.021
| getChannelMembers | Avg| 6ms| 11ms | 5ms | 84.421
| | P99| 24ms| 49ms | 25ms | 103.737
| getChannelMembersForTeamForUser | Avg| 12ms| 11ms | -1ms | -8.319
| | P99| 102ms| 99ms | -3ms | -2.953
| getChannelMembersForUser | Avg| 20ms| 36ms | 16ms | 81.856
| | P99| 49ms| 99ms | 50ms | 102.041
| getChannelStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 189ms| 177ms | -12ms | -6.352
| getChannelUnread | Avg| 12ms| 11ms | -1ms | -8.426
| | P99| 99ms| 97ms | -2ms | -2.016
| getChannelsForTeamForUser | Avg| 11ms| 10ms | -1ms | -9.035
| | P99| 115ms| 99ms | -16ms | -13.898
| getChannelsForUser | Avg| 12ms| 10ms | -2ms | -17.287
| | P99| 98ms| 98ms | 0s | 0.000
| getClientConfig | Avg| 16ms| 14ms | -2ms | -12.741
| | P99| 227ms| 209ms | -18ms | -7.943
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 72ms| 69ms | -3ms | -4.183
| | P99| 403ms| 366ms | -37ms | -9.171
| getFileThumbnail | Avg| 61ms| 57ms | -4ms | -6.610
| | P99| 363ms| 308ms | -55ms | -15.158
| getFilteredUsersStats | Avg| 36ms| 48ms | 12ms | 33.338
| | P99| 98ms| 99ms | 1ms | 1.026
| getGroups | Avg| 17ms| 4ms | -13ms | -75.399
| | P99| 50ms| 10ms | -40ms | -80.808
| getGroupsAssociatedToChannelsByTeam | Avg| 26ms| 2ms | -24ms | -93.346
| | P99| 50ms| 5ms | -45ms | -90.452
| getJobsByType | Avg| 9ms| 7ms | -2ms | -22.558
| | P99| 48ms| 93ms | 45ms | 94.232
| getLicenseSelfServeStatus | Avg| 70ms| 91ms | 21ms | 30.151
| | P99| 100ms| 244ms | 144ms | 144.724
| getPluginStatuses | Avg| 30ms| 0s | -30ms | -98.987
| | P99| 50ms| 0s | -50ms | -100.451
| getPostThread | Avg| 54ms| 46ms | -8ms | -14.879
| | P99| 478ms| 448ms | -30ms | -6.270
| getPostsForChannel | Avg| 92ms| 85ms | -7ms | -7.577
| | P99| 963ms| 903ms | -60ms | -6.230
| getPostsForChannelAroundLastUnread | Avg| 43ms| 40ms | -3ms | -6.985
| | P99| 468ms| 434ms | -34ms | -7.268
| getPreferences | Avg| 9ms| 8ms | -1ms | -11.305
| | P99| 98ms| 91ms | -7ms | -7.137
| getPrevTrialLicense | Avg| 5ms| 9ms | 4ms | 85.993
| | P99| 24ms| 49ms | 25ms | 103.413
| getProductNotices | Avg| 10ms| 12ms | 2ms | 19.249
| | P99| 25ms| 25ms | 0s | 0.000
| getProfileImage | Avg| 97ms| 91ms | -6ms | -6.164
| | P99| 488ms| 481ms | -7ms | -1.435
| getPublicChannelsForTeam | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 210ms| 189ms | -21ms | -9.984
| getRolesByNames | Avg| 5ms| 1ms | -4ms | -78.831
| | P99| 10ms| 9ms | -1ms | -10.050
| getTeamMember | Avg| 10ms| 8ms | -2ms | -20.510
| | P99| 138ms| 92ms | -46ms | -33.296
| getTeamMembersForUser | Avg| 9ms| 8ms | -1ms | -10.800
| | P99| 100ms| 97ms | -3ms | -3.006
| getTeamsForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 92ms| 84ms | -8ms | -8.700
| getTeamsUnreadForUser | Avg| 14ms| 13ms | -1ms | -6.907
| | P99| 198ms| 174ms | -24ms | -12.096
| getThreadsForUser | Avg| 14ms| 12ms | -2ms | -14.775
| | P99| 143ms| 111ms | -32ms | -22.336
| getUser | Avg| 12ms| 11ms | -1ms | -8.375
| | P99| 214ms| 210ms | -4ms | -1.865
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.520
| getUsers | Avg| 15ms| 13ms | -2ms | -13.222
| | P99| 232ms| 207ms | -25ms | -10.792
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 37ms| 32ms | -5ms | -13.600
| getUsersByNames | Avg| 11ms| 10ms | -1ms | -9.172
| | P99| 100ms| 96ms | -4ms | -4.007
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 159ms| 141ms | -18ms | -11.316
| | P99| 1.32s| 964ms | -356ms | -26.967
| logout | Avg| 141ms| 137ms | -4ms | -2.828
| | P99| 855ms| 480ms | -375ms | -43.863
| patchPost | Avg| 191ms| 97ms | -94ms | -49.207
| | P99| 2.38s| 840ms | -1.54s | -64.706
| removeUserCustomStatus | Avg| 285ms| 304ms | 19ms | 6.659
| | P99| 1.518s| 2.173s | 655ms | 43.163
| root | Avg| 0s| 10ms | 10ms | 5511.842
| | P99| 5ms| 235ms | 230ms | 4646.465
| saveReaction | Avg| 35ms| 32ms | -3ms | -8.541
| | P99| 249ms| 247ms | -2ms | -0.803
| searchAllChannels | Avg| 67ms| 66ms | -1ms | -1.491
| | P99| 315ms| 263ms | -52ms | -16.534
| searchGroupChannels | Avg| 14ms| 20ms | 6ms | 43.960
| | P99| 132ms| 140ms | 8ms | 6.072
| searchPostsInTeam | Avg| 277ms| 247ms | -30ms | -10.819
| | P99| 3.579s| 2.457s | -1.122s | -31.348
| searchUsers | Avg| 63ms| 60ms | -3ms | -4.798
| | P99| 247ms| 246ms | -1ms | -0.404
| setPostReminder | Avg| 69ms| 56ms | -13ms | -18.842
| | P99| 880ms| 445ms | -435ms | -49.431
| unfollowThreadByUser | Avg| 52ms| 53ms | 1ms | 1.922
| | P99| 420ms| 430ms | 10ms | 2.381
| updateCategoriesForTeamForUser | Avg| 157ms| 130ms | -27ms | -17.176
| | P99| 1.825s| 1.885s | 60ms | 3.288
| updatePreferences | Avg| 32ms| 26ms | -6ms | -18.827
| | P99| 363ms| 247ms | -116ms | -31.995
| updateReadStateAllThreadsByUser | Avg| 15ms| 0s | -15ms | -101.779
| | P99| 50ms| 0s | -50ms | -101.010
| updateReadStateThreadByUser | Avg| 129ms| 115ms | -14ms | -10.887
| | P99| 917ms| 853ms | -64ms | -6.977
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 495ms| 489ms | -6ms | -1.212
| | P99| 2.142s| 2.13s | -12ms | -0.560
| upsertDraft | Avg| 56ms| 3ms | -53ms | -94.788
| | P99| 100ms| 5ms | -95ms | -95.477
| viewChannel | Avg| 35ms| 32ms | -3ms | -8.488
| | P99| 403ms| 359ms | -44ms | -10.915
