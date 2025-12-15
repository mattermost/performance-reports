### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 36ms | 34ms | 1492.00
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 2ms | 13ms | 11ms | 442.52
| JobStore.Get | avg | 18ms | 92ms | 74ms | 408.70
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 6ms | 26ms | 20ms | 312.69
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 5ms | 17ms | 12ms | 259.31
| PostStore.GetPostReminders | avg | 15ms | 52ms | 37ms | 245.18
| LicenseStore.GetAll | avg | 12ms | 38ms | 26ms | 215.58
| ChannelBookmarkStore.Save | avg | 21ms | 65ms | 44ms | 213.67
| JobStore.GetNewestJobByStatusesAndType | avg | 7ms | 21ms | 14ms | 208.93
| PostStore.AnalyticsPostCount | avg | 104ms | 302ms | 198ms | 190.54
| JobStore.GetCountByStatusAndType | avg | 9ms | 25ms | 16ms | 173.48
| TeamStore.AnalyticsTeamCount | avg | 13ms | 34ms | 21ms | 160.07
| LinkMetadataStore.Save | avg | 7ms | 19ms | 12ms | 160.03
| ChannelBookmarkStore.Get | avg | 4ms | 11ms | 7ms | 157.04
| JobStore.Save | avg | 7ms | 18ms | 11ms | 156.30
| ScheduledPostStore.GetPendingScheduledPosts | avg | 13ms | 29ms | 16ms | 126.93
| ComplianceStore.MessageExport | avg | 265ms | 563ms | 298ms | 112.43
| BotStore.Get | avg | 9ms | 17ms | 8ms | 89.45
| ProductNoticesStore.ClearOldNotices | avg | 35ms | 60ms | 25ms | 71.07
| TokenStore.Cleanup | avg | 22ms | 36ms | 14ms | 64.39
| ChannelStore.AutocompleteInTeamForSearch | avg | 81ms | 132ms | 51ms | 63.11
| PostStore.GetPostReminderMetadata | avg | 10ms | 16ms | 6ms | 60.77
| ChannelStore.GetTeamChannels | avg | 26ms | 40ms | 14ms | 53.89
| EmojiStore.GetMultipleByName | avg | 35ms | 53ms | 18ms | 51.00
| StatusStore.UpdateExpiredDNDStatuses | avg | 10ms | 15ms | 5ms | 48.55
| RoleStore.ChannelHigherScopedPermissions | avg | 44ms | 63ms | 19ms | 42.73
| ChannelStore.UpdateSidebarCategories | avg | 74ms | 97ms | 23ms | 31.25
| JobStore.UpdateStatus | avg | 10ms | 13ms | 3ms | 28.91
| RoleStore.GetByNames | avg | 63ms | 79ms | 16ms | 25.48
| ThreadStore.Get | avg | 8ms | 10ms | 2ms | 24.79
| JobStore.UpdateOptimistically | avg | 9ms | 11ms | 2ms | 22.92
| PropertyValueStore.SearchPropertyValues | avg | 15ms | 18ms | 3ms | 20.30
| ScheduledPostStore.CreateScheduledPost | avg | 10ms | 12ms | 2ms | 19.26
| PostPersistentNotificationStore.Get | avg | 11ms | 13ms | 2ms | 18.80
| PostStore.GetPostsByThread | avg | 18ms | 21ms | 3ms | 16.36
| FileInfoStore.GetByIds | avg | 14ms | 16ms | 2ms | 14.12
| ChannelStore.GetPublicChannelsForTeam | avg | 28ms | 32ms | 4ms | 14.09
| UserStore.Update | avg | 30ms | 34ms | 4ms | 13.27
| ChannelStore.Get | avg | 23ms | 26ms | 3ms | 13.02
| ChannelStore.GetChannelUnread | avg | 16ms | 18ms | 2ms | 12.76
| UserStore.GetByUsername | avg | 16ms | 18ms | 2ms | 12.75
| PostAcknowledgementStore.GetForPosts | avg | 17ms | 19ms | 2ms | 11.85
| ChannelStore.SearchGroupChannels | avg | 17ms | 19ms | 2ms | 11.58
| PostPriorityStore.GetForPosts | avg | 18ms | 20ms | 2ms | 11.38
| DraftStore.Get | avg | 18ms | 20ms | 2ms | 11.09
| ThreadStore.GetThreadsForUser | avg | 18ms | 20ms | 2ms | 10.99
| ChannelStore.GetMemberForPost | avg | 20ms | 22ms | 2ms | 10.01
| ChannelStore.AnalyticsCountAll | avg | 42ms | 46ms | 4ms | 9.60
| ThreadStore.GetThreadUnreadReplyCount | avg | 21ms | 23ms | 2ms | 9.34
| PostStore.SetPostReminder | avg | 38ms | 41ms | 3ms | 7.97
| ChannelStore.Save | avg | 51ms | 55ms | 4ms | 7.84
| PostStore.GetPostsSince | avg | 27ms | 29ms | 2ms | 7.37
| PostStore.Get | avg | 32ms | 34ms | 2ms | 6.28
| UserStore.AutocompleteUsersInChannel | avg | 69ms | 73ms | 4ms | 5.80
| PostStore.SearchPostsForUser | avg | 149ms | 152ms | 3ms | 2.02
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 99ms | 94ms | 1898.99
| ChannelStore.AutocompleteInTeamForSearch | p99 | 444ms | 3.271s | 2.827s | 636.71
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 25ms | 20ms | 403.90
| TokenStore.Cleanup | p99 | 49ms | 244ms | 195ms | 397.96
| JobStore.Get | p99 | 97ms | 475ms | 378ms | 390.70
| JobStore.GetNewestJobByStatusesAndType | p99 | 87ms | 370ms | 283ms | 326.54
| JobStore.Save | p99 | 79ms | 310ms | 231ms | 291.48
| ChannelStore.CreateSidebarCategory | p99 | 249ms | 970ms | 721ms | 290.14
| PostStore.GetPostReminders | p99 | 227ms | 865ms | 638ms | 281.37
| LinkMetadataStore.Save | p99 | 65ms | 212ms | 147ms | 224.43
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 84ms | 210ms | 126ms | 149.11
| ChannelStore.UpdateSidebarCategories | p99 | 670ms | 1.57s | 900ms | 134.33
| BotStore.Get | p99 | 93ms | 210ms | 117ms | 126.49
| JobStore.UpdateOptimistically | p99 | 89ms | 195ms | 106ms | 118.55
| JobStore.GetCountByStatusAndType | p99 | 104ms | 227ms | 123ms | 117.70
| JobStore.UpdateStatus | p99 | 90ms | 193ms | 103ms | 114.93
| ChannelBookmarkStore.Get | p99 | 24ms | 49ms | 25ms | 105.04
| TeamStore.AnalyticsTeamCount | p99 | 48ms | 98ms | 50ms | 103.09
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 24ms | 49ms | 25ms | 103.09
| SessionStore.Remove | p99 | 89ms | 180ms | 91ms | 102.53
| LicenseStore.GetAll | p99 | 49ms | 99ms | 50ms | 102.30
| PostStore.AnalyticsPostCount | p99 | 493ms | 985ms | 492ms | 99.90
| ChannelBookmarkStore.Save | p99 | 229ms | 455ms | 226ms | 98.69
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 99ms | 49ms | 98.47
| UserStore.GetProfilesInChannel | p99 | 241ms | 450ms | 209ms | 86.90
| RoleStore.GetByNames | p99 | 473ms | 830ms | 357ms | 75.42
| UserStore.Update | p99 | 233ms | 363ms | 130ms | 55.81
| StatusStore.UpdateExpiredDNDStatuses | p99 | 130ms | 198ms | 68ms | 52.31
| ChannelStore.Get | p99 | 238ms | 339ms | 101ms | 42.35
| ThreadStore.GetThreadFollowers | p99 | 131ms | 177ms | 46ms | 35.09
| PostPersistentNotificationStore.GetSingle | p99 | 137ms | 180ms | 43ms | 31.38
| ChannelStore.GetSidebarCategory | p99 | 343ms | 450ms | 107ms | 31.24
| ThreadStore.Get | p99 | 79ms | 98ms | 19ms | 23.95
| TeamStore.Get | p99 | 147ms | 181ms | 34ms | 23.18
| PostStore.GetSingle | p99 | 157ms | 191ms | 34ms | 21.70
| EmojiStore.GetByName | p99 | 170ms | 205ms | 35ms | 20.58
| PostStore.Get | p99 | 343ms | 409ms | 66ms | 19.25
| LinkMetadataStore.Get | p99 | 165ms | 195ms | 30ms | 18.22
| ChannelStore.GetChannelUnread | p99 | 209ms | 247ms | 38ms | 18.20
| GroupStore.GetGroups | p99 | 164ms | 188ms | 24ms | 14.63
| FileInfoStore.GetByIds | p99 | 207ms | 236ms | 29ms | 14.04
| PostStore.GetPostsByThread | p99 | 186ms | 212ms | 26ms | 13.95
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 203ms | 230ms | 27ms | 13.27
| UserStore.GetUnreadCount | p99 | 177ms | 199ms | 22ms | 12.40
| PropertyValueStore.SearchPropertyValues | p99 | 206ms | 231ms | 25ms | 12.15
| RoleStore.ChannelHigherScopedPermissions | p99 | 439ms | 492ms | 53ms | 12.08
| UserStore.AutocompleteUsersInChannel | p99 | 383ms | 428ms | 45ms | 11.75
| ThreadStore.GetMembershipForUser | p99 | 188ms | 210ms | 22ms | 11.68
| ChannelStore.SearchGroupChannels | p99 | 207ms | 229ms | 22ms | 10.63
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 86ms | 95ms | 9ms | 10.53
| DraftStore.GetDraftsForUser | p99 | 225ms | 248ms | 23ms | 10.21
| FileInfoStore.Get | p99 | 198ms | 218ms | 20ms | 10.08
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 169ms | 186ms | 17ms | 10.03
| ChannelStore.Save | p99 | 449ms | 494ms | 45ms | 10.03
| PostPriorityStore.GetForPosts | p99 | 236ms | 258ms | 22ms | 9.34
| UserStore.GetByUsername | p99 | 208ms | 227ms | 19ms | 9.13
| JobStore.GetAllByStatus | p99 | 207ms | 225ms | 18ms | 8.68
| DraftStore.Get | p99 | 224ms | 243ms | 19ms | 8.50
| FileInfoStore.GetForPost | p99 | 183ms | 198ms | 15ms | 8.18
| ThreadStore.GetThreadUnreadReplyCount | p99 | 204ms | 220ms | 16ms | 7.85
| ChannelStore.GetPinnedPostCount | p99 | 183ms | 197ms | 14ms | 7.66
| ChannelStore.GetMemberForPost | p99 | 222ms | 239ms | 17ms | 7.65
| PostStore.GetPostsAfter | p99 | 185ms | 199ms | 14ms | 7.59
| ThreadStore.GetThreadsForUser | p99 | 217ms | 233ms | 16ms | 7.36
| ChannelStore.GetPublicChannelsForTeam | p99 | 222ms | 238ms | 16ms | 7.22
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 185ms | 198ms | 13ms | 7.03
| PreferenceStore.Get | p99 | 204ms | 218ms | 14ms | 6.86
| PostAcknowledgementStore.GetForPosts | p99 | 234ms | 250ms | 16ms | 6.84
| StatusStore.GetByIds | p99 | 227ms | 242ms | 15ms | 6.61
| ChannelStore.GetChannels | p99 | 212ms | 226ms | 14ms | 6.60
| WebhookStore.GetOutgoingByTeam | p99 | 217ms | 231ms | 14ms | 6.46
| ChannelStore.CreateDirectChannel | p99 | 798ms | 846ms | 48ms | 6.01
| ChannelStore.GetMembersForUser | p99 | 207ms | 219ms | 12ms | 5.81
| PostPersistentNotificationStore.Get | p99 | 173ms | 183ms | 10ms | 5.76
| UserStore.GetProfileByIds | p99 | 204ms | 214ms | 10ms | 4.90
| PostStore.GetPostsSince | p99 | 228ms | 239ms | 11ms | 4.83
| PostStore.GetPostsBefore | p99 | 211ms | 220ms | 9ms | 4.27
| ReactionStore.GetForPost | p99 | 181ms | 188ms | 7ms | 3.87
| ThreadStore.GetThreadForUser | p99 | 238ms | 246ms | 8ms | 3.37
| PostStore.GetEtag | p99 | 208ms | 215ms | 7ms | 3.36
| StatusStore.SaveOrUpdateMany | p99 | 214ms | 221ms | 7ms | 3.28
| UserStore.Get | p99 | 181ms | 186ms | 5ms | 2.76
| ChannelStore.GetAllChannelMembersForUser | p99 | 186ms | 191ms | 5ms | 2.69
| UserStore.GetProfilesByUsernames | p99 | 210ms | 215ms | 5ms | 2.38
| PreferenceStore.DeleteCategoryAndName | p99 | 93ms | 95ms | 2ms | 2.16
| UserStore.Search | p99 | 243ms | 248ms | 5ms | 2.06
| ComplianceStore.MessageExport | p99 | 975ms | 995ms | 20ms | 2.05
| ClusterDiscoveryStore.SetLastPingAt | p99 | 216ms | 220ms | 4ms | 1.85
| ThreadStore.GetTotalUnreadMentions | p99 | 162ms | 165ms | 3ms | 1.85
| StatusStore.Get | p99 | 168ms | 170ms | 2ms | 1.19
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 174ms | 176ms | 2ms | 1.15
| ThreadStore.GetTeamsUnreadForUser | p99 | 199ms | 201ms | 2ms | 1.00
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -103.80
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | avg | 68ms | 0s | -68ms | -100.22
| RetentionPolicyStore.GetCount | avg | 57ms | 0s | -57ms | -100.18
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -98.12
| ChannelStore.GetMany | avg | 3ms | 0s | -3ms | -97.70
| ChannelStore.GetByNameIncludeDeleted | avg | 14ms | 0s | -14ms | -97.02
| FileInfoStore.Search | avg | 14ms | 0s | -14ms | -96.65
| EmojiStore.Search | avg | 2ms | 0s | -2ms | -96.12
| JobStore.GetAllByTypesAndStatusesPage | avg | 2ms | 0s | -2ms | -91.28
| ChannelBookmarkStore.UpdateSortOrder | avg | 25ms | 3ms | -22ms | -87.47
| ChannelStore.GetMembers | avg | 43ms | 17ms | -26ms | -60.03
| JobStore.GetAllByTypePage | avg | 17ms | 8ms | -9ms | -53.57
| PostStore.Delete | avg | 53ms | 35ms | -18ms | -34.25
| ChannelStore.CreateSidebarCategory | avg | 222ms | 149ms | -73ms | -32.85
| PostStore.GetPostIdBeforeTime | avg | 10ms | 7ms | -3ms | -30.62
| CommandWebhookStore.Cleanup | avg | 35ms | 25ms | -10ms | -28.69
| SessionStore.GetSessionsExpired | avg | 15ms | 11ms | -4ms | -27.24
| TeamStore.GetActiveMemberCount | avg | 84ms | 62ms | -22ms | -26.31
| PostStore.AnalyticsPostCountByTeam | avg | 28ms | 22ms | -6ms | -21.52
| TeamStore.GetTotalMemberCount | avg | 64ms | 52ms | -12ms | -18.85
| UserAccessTokenStore.GetByToken | avg | 11ms | 9ms | -2ms | -18.42
| ChannelStore.CreateInitialSidebarCategories | avg | 33ms | 27ms | -6ms | -18.17
| SessionStore.Remove | avg | 12ms | 10ms | -2ms | -17.11
| ProductNoticesStore.View | avg | 90ms | 75ms | -15ms | -16.74
| UserStore.GetMany | avg | 12ms | 10ms | -2ms | -16.07
| ThreadStore.MarkAllAsReadByChannels | avg | 13ms | 11ms | -2ms | -15.71
| UserStore.GetProfilesInChannel | avg | 35ms | 30ms | -5ms | -14.49
| SessionStore.Get | avg | 19ms | 17ms | -2ms | -10.26
| ClusterDiscoveryStore.SetLastPingAt | avg | 21ms | 19ms | -2ms | -9.42
| TeamStore.SaveMember | avg | 36ms | 33ms | -3ms | -8.34
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 77ms | 71ms | -6ms | -7.75
| ChannelStore.SaveMember | avg | 65ms | 60ms | -5ms | -7.65
| PreferenceStore.Save | avg | 27ms | 25ms | -2ms | -7.30
| PostStore.Save | avg | 37ms | 35ms | -2ms | -5.38
| UserStore.AnalyticsActiveCount | avg | 39ms | 37ms | -2ms | -5.07
| UserStore.GetAllProfilesInChannel | avg | 356ms | 338ms | -18ms | -5.05
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | p99 | 25ms | 0s | -25ms | -101.21
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.00
| ChannelStore.GetMany | p99 | 5ms | 0s | -5ms | -100.97
| JobStore.GetAllByTypesAndStatusesPage | p99 | 5ms | 0s | -5ms | -100.97
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | p99 | 100ms | 0s | -100ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 31ms | 0s | -31ms | -100.00
| RetentionPolicyStore.GetCount | p99 | 247ms | 0s | -247ms | -100.00
| ChannelStore.GetByNameIncludeDeleted | p99 | 96ms | 0s | -96ms | -99.48
| ChannelBookmarkStore.UpdateSortOrder | p99 | 97ms | 5ms | -92ms | -94.36
| ChannelStore.GetMembers | p99 | 244ms | 49ms | -195ms | -79.92
| PostStore.AnalyticsPostCountByTeam | p99 | 241ms | 99ms | -142ms | -58.92
| ChannelStore.AnalyticsCountAll | p99 | 241ms | 99ms | -142ms | -58.92
| UserStore.AnalyticsActiveCount | p99 | 232ms | 97ms | -135ms | -58.19
| JobStore.GetAllByTypePage | p99 | 214ms | 90ms | -124ms | -57.94
| PostStore.SetPostReminder | p99 | 855ms | 385ms | -470ms | -54.97
| UserStore.GetMany | p99 | 199ms | 92ms | -107ms | -53.77
| SessionStore.GetSessionsExpired | p99 | 94ms | 47ms | -47ms | -50.00
| PostStore.Delete | p99 | 427ms | 218ms | -209ms | -48.89
| TeamStore.GetActiveMemberCount | p99 | 462ms | 237ms | -225ms | -48.65
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 411ms | 238ms | -173ms | -42.10
| PostStore.GetPostIdBeforeTime | p99 | 152ms | 96ms | -56ms | -36.80
| PostStore.GetPostReminderMetadata | p99 | 169ms | 115ms | -54ms | -31.95
| ChannelStore.GetMembersForUserWithPagination | p99 | 142ms | 99ms | -43ms | -30.25
| UserStore.Save | p99 | 737ms | 522ms | -215ms | -29.17
| UserStore.GetForLogin | p99 | 136ms | 99ms | -37ms | -27.18
| GroupStore.GetByName | p99 | 124ms | 91ms | -33ms | -26.66
| ChannelStore.GetMember | p99 | 135ms | 100ms | -35ms | -25.87
| ThreadStore.MarkAllAsReadByChannels | p99 | 183ms | 136ms | -47ms | -25.64
| TeamStore.GetTeamsForUser | p99 | 134ms | 100ms | -34ms | -25.39
| PropertyFieldStore.SearchPropertyFields | p99 | 144ms | 108ms | -36ms | -24.94
| TeamStore.GetAllPage | p99 | 144ms | 110ms | -34ms | -23.69
| DraftStore.Delete | p99 | 191ms | 149ms | -42ms | -21.98
| TeamStore.GetTeamsByUserId | p99 | 141ms | 113ms | -28ms | -19.82
| ScheduledPostStore.CreateScheduledPost | p99 | 182ms | 146ms | -36ms | -19.73
| PreferenceStore.Save | p99 | 337ms | 272ms | -65ms | -19.30
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 86ms | 70ms | -16ms | -18.61
| PostStore.Update | p99 | 408ms | 335ms | -73ms | -17.88
| ChannelStore.CreateInitialSidebarCategories | p99 | 426ms | 350ms | -76ms | -17.82
| ChannelStore.IncrementMentionCount | p99 | 145ms | 120ms | -25ms | -17.24
| UserStore.IsEmpty | p99 | 59ms | 49ms | -10ms | -17.08
| ChannelStore.SaveMember | p99 | 580ms | 482ms | -98ms | -16.90
| ChannelStore.GetByName | p99 | 140ms | 117ms | -23ms | -16.43
| ChannelStore.UpdateLastViewedAt | p99 | 138ms | 116ms | -22ms | -15.99
| ChannelStore.GetGuestCount | p99 | 173ms | 146ms | -27ms | -15.65
| UserTermsOfServiceStore.GetByUser | p99 | 117ms | 99ms | -18ms | -15.40
| PostStore.GetPostIdAfterTime | p99 | 88ms | 75ms | -13ms | -14.71
| PreferenceStore.GetAll | p99 | 161ms | 138ms | -23ms | -14.29
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 144ms | 124ms | -20ms | -13.87
| ProductNoticesStore.View | p99 | 968ms | 836ms | -132ms | -13.63
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 133ms | 115ms | -18ms | -13.57
| StatusStore.UpdateLastActivityAt | p99 | 118ms | 103ms | -15ms | -12.67
| UserStore.UpdateUpdateAt | p99 | 88ms | 77ms | -11ms | -12.54
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 97ms | 85ms | -12ms | -12.42
| SessionStore.Save | p99 | 205ms | 180ms | -25ms | -12.21
| UserStore.UpdateLastLogin | p99 | 91ms | 80ms | -11ms | -12.14
| SessionStore.UpdateLastActivityAt | p99 | 113ms | 100ms | -13ms | -11.51
| TeamStore.GetMember | p99 | 93ms | 84ms | -9ms | -9.70
| PostAcknowledgementStore.GetForPost | p99 | 97ms | 89ms | -8ms | -8.24
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 104ms | 96ms | -8ms | -7.72
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 220ms | 204ms | -16ms | -7.28
| JobStore.UpdateStatusOptimistically | p99 | 208ms | 193ms | -15ms | -7.19
| SystemStore.GetByName | p99 | 99ms | 92ms | -7ms | -7.04
| TeamStore.GetTotalMemberCount | p99 | 239ms | 223ms | -16ms | -6.70
| ThreadStore.UpdateMembership | p99 | 106ms | 99ms | -7ms | -6.63
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 153ms | 143ms | -10ms | -6.56
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 375ms | 351ms | -24ms | -6.40
| AuditStore.Save | p99 | 99ms | 93ms | -6ms | -6.06
| SessionStore.Get | p99 | 231ms | 217ms | -14ms | -6.05
| UserStore.UpdateFailedPasswordAttempts | p99 | 99ms | 93ms | -6ms | -6.05
| UserStore.GetAllProfilesInChannel | p99 | 2.149s | 2.02s | -129ms | -6.00
| ThreadStore.GetTotalUnreadThreads | p99 | 143ms | 135ms | -8ms | -5.59
| ChannelStore.GetFileCount | p99 | 200ms | 189ms | -11ms | -5.49
| ChannelStore.GetChannelsByUser | p99 | 129ms | 122ms | -7ms | -5.44
| UserStore.GetAllProfiles | p99 | 92ms | 87ms | -5ms | -5.41
| PostPersistentNotificationStore.DeleteExpired | p99 | 94ms | 89ms | -5ms | -5.34
| PostStore.SearchPostsForUser | p99 | 2.278s | 2.159s | -119ms | -5.22
| PostStore.GetPosts | p99 | 97ms | 92ms | -5ms | -5.15
| SessionStore.GetLRUSessions | p99 | 99ms | 94ms | -5ms | -5.03
| FileInfoStore.Save | p99 | 200ms | 190ms | -10ms | -5.00
| TeamStore.SaveMember | p99 | 241ms | 229ms | -12ms | -4.98
| FileInfoStore.SetContent | p99 | 241ms | 229ms | -12ms | -4.97
| UserStore.Count | p99 | 190ms | 181ms | -9ms | -4.74
| PostStore.Save | p99 | 438ms | 419ms | -19ms | -4.34
| StatusStore.SaveOrUpdate | p99 | 177ms | 170ms | -7ms | -3.95
| ChannelStore.GetMemberLastViewedAt | p99 | 99ms | 96ms | -3ms | -3.03
| ThreadStore.GetTotalThreads | p99 | 147ms | 143ms | -4ms | -2.71
| DraftStore.Upsert | p99 | 199ms | 195ms | -4ms | -2.01
| ChannelStore.GetTeamChannels | p99 | 227ms | 223ms | -4ms | -1.76
| ChannelStore.GetMemberCount | p99 | 222ms | 219ms | -3ms | -1.35
| EmojiStore.GetMultipleByName | p99 | 239ms | 236ms | -3ms | -1.25
| ThreadStore.MaintainMembership | p99 | 247ms | 244ms | -3ms | -1.22
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 24ms | 22ms | 897.04
| getPrevTrialLicense | avg | 12ms | 77ms | 65ms | 539.48
| getRolesByNames | avg | 5ms | 17ms | 12ms | 224.74
| createChannelBookmark | avg | 35ms | 94ms | 59ms | 166.44
| handleCheckCWSConnection | avg | 83ms | 168ms | 85ms | 102.62
| autocompleteChannelsForTeamForSearch | avg | 81ms | 132ms | 51ms | 62.88
| getServerLimits | avg | 36ms | 58ms | 22ms | 60.42
| getAnalytics | avg | 254ms | 374ms | 120ms | 47.25
| unfollowThreadByUser | avg | 50ms | 68ms | 18ms | 36.17
| createChannel | avg | 318ms | 423ms | 105ms | 32.99
| updateChannelBookmark | avg | 32ms | 42ms | 10ms | 31.39
| updateReadStateAllThreadsByUser | avg | 7ms | 9ms | 2ms | 27.20
| listCPAValues | avg | 15ms | 19ms | 4ms | 25.83
| followThreadByUser | avg | 51ms | 64ms | 13ms | 25.72
| patchPost | avg | 101ms | 122ms | 21ms | 20.72
| updateCategoriesForTeamForUser | avg | 142ms | 169ms | 27ms | 18.95
| getChannelUnread | avg | 18ms | 21ms | 3ms | 17.10
| setPostReminder | avg | 84ms | 97ms | 13ms | 15.40
| getPostThread | avg | 75ms | 86ms | 11ms | 14.63
| getPublicChannelsForTeam | avg | 30ms | 34ms | 4ms | 13.53
| createGroupChannel | avg | 865ms | 974ms | 109ms | 12.59
| getFilteredUsersStats | avg | 17ms | 19ms | 2ms | 11.85
| searchGroupChannels | avg | 18ms | 20ms | 2ms | 11.35
| getPostsForChannel | avg | 128ms | 142ms | 14ms | 10.94
| saveReaction | avg | 46ms | 51ms | 5ms | 10.83
| deleteDraft | avg | 19ms | 21ms | 2ms | 10.46
| updateReadStateThreadByUser | avg | 153ms | 168ms | 15ms | 9.79
| autocompleteUsers | avg | 65ms | 70ms | 5ms | 7.69
| addChannelMember | avg | 498ms | 536ms | 38ms | 7.63
| getFileThumbnail | avg | 64ms | 67ms | 3ms | 4.69
| viewChannel | avg | 55ms | 57ms | 2ms | 3.64
| searchPostsInTeam | avg | 180ms | 186ms | 6ms | 3.32
| getFilePreview | avg | 71ms | 73ms | 2ms | 2.83
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | p99 | 10ms | 98ms | 88ms | 884.42
| autocompleteChannelsForTeamForSearch | p99 | 444ms | 3.271s | 2.827s | 636.71
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 25ms | 20ms | 404.04
| createChannelBookmark | p99 | 234ms | 935ms | 701ms | 300.21
| createChannel | p99 | 925ms | 2.365s | 1.44s | 155.68
| handleCheckCWSConnection | p99 | 100ms | 249ms | 149ms | 149.73
| updateUserCustomStatus | p99 | 5ms | 12ms | 7ms | 140.75
| updateCategoriesForTeamForUser | p99 | 1.525s | 3.45s | 1.925s | 126.23
| getPrevTrialLicense | p99 | 49ms | 100ms | 51ms | 104.08
| updateChannelBookmark | p99 | 50ms | 98ms | 48ms | 96.48
| createCategoryForTeamForUser | p99 | 495ms | 970ms | 475ms | 95.96
| followThreadByUser | p99 | 425ms | 800ms | 375ms | 88.23
| createGroupChannel | p99 | 4.525s | 7.387s | 2.862s | 63.25
| updateReadStateThreadByUser | p99 | 1.203s | 1.906s | 703ms | 58.44
| getChannelUnread | p99 | 230ms | 353ms | 123ms | 53.52
| patchPost | p99 | 922ms | 1.255s | 333ms | 36.11
| saveReaction | p99 | 456ms | 595ms | 139ms | 30.46
| getPostThread | p99 | 752ms | 981ms | 229ms | 30.44
| addChannelMember | p99 | 3.471s | 4.525s | 1.054s | 30.37
| createPost | p99 | 4.962s | 5.818s | 856ms | 17.25
| getPostsForChannel | p99 | 1.757s | 2.055s | 298ms | 16.96
| getDrafts | p99 | 233ms | 272ms | 39ms | 16.71
| listCPAValues | p99 | 210ms | 241ms | 31ms | 14.73
| autocompleteUsers | p99 | 396ms | 448ms | 52ms | 13.12
| viewChannel | p99 | 631ms | 701ms | 70ms | 11.09
| searchGroupChannels | p99 | 210ms | 231ms | 21ms | 9.99
| getTeamMember | p99 | 184ms | 199ms | 15ms | 8.14
| getFileThumbnail | p99 | 422ms | 454ms | 32ms | 7.59
| deleteDraft | p99 | 230ms | 247ms | 17ms | 7.38
| getPublicChannelsForTeam | p99 | 222ms | 238ms | 16ms | 7.22
| getChannelsForTeamForUser | p99 | 216ms | 230ms | 14ms | 6.48
| getChannelMembersForTeamForUser | p99 | 210ms | 223ms | 13ms | 6.18
| getThreadsForUser | p99 | 223ms | 236ms | 13ms | 5.82
| getFilePreview | p99 | 447ms | 473ms | 26ms | 5.82
| updatePreferences | p99 | 454ms | 474ms | 20ms | 4.41
| removeUserCustomStatus | p99 | 2.231s | 2.311s | 80ms | 3.59
| searchUsers | p99 | 245ms | 252ms | 7ms | 2.85
| getUsersByNames | p99 | 216ms | 221ms | 5ms | 2.31
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 3ms | 0s | -3ms | -115.03
| createJob | avg | 26ms | 0s | -26ms | -101.93
| deleteChannelBookmark | avg | 31ms | 0s | -31ms | -101.05
| searchFilesInTeam | avg | 73ms | 0s | -73ms | -100.17
| getConfig | avg | 129ms | 0s | -129ms | -100.08
| getUsersByGroupChannelIds | avg | 5ms | 0s | -5ms | -93.90
| autocompleteEmojis | avg | 2ms | 0s | -2ms | -93.61
| channelMemberCountsByGroup | avg | 4ms | 0s | -4ms | -90.31
| updateChannelBookmarkSortOrder | avg | 28ms | 3ms | -25ms | -89.10
| getJobsByType | avg | 18ms | 8ms | -10ms | -57.07
| deletePost | avg | 104ms | 58ms | -46ms | -44.27
| getChannelMembers | avg | 44ms | 27ms | -17ms | -38.75
| createCategoryForTeamForUser | avg | 245ms | 175ms | -70ms | -28.55
| getTeamStats | avg | 91ms | 65ms | -26ms | -28.43
| getClientConfig | avg | 22ms | 18ms | -4ms | -18.53
| getChannel | avg | 28ms | 23ms | -5ms | -17.85
| listCPAFields | avg | 12ms | 10ms | -2ms | -17.33
| getUsers | avg | 17ms | 15ms | -2ms | -11.88
| logout | avg | 159ms | 141ms | -18ms | -11.29
| addTeamMember | avg | 1.384s | 1.233s | -151ms | -10.91
| getUser | avg | 19ms | 17ms | -2ms | -10.75
| createDirectChannel | avg | 548ms | 495ms | -53ms | -9.68
| getChannelMember | avg | 22ms | 20ms | -2ms | -9.07
| createUser | avg | 398ms | 373ms | -25ms | -6.28
| getPostsForChannelAroundLastUnread | avg | 55ms | 52ms | -3ms | -5.48
| removeUserCustomStatus | avg | 341ms | 323ms | -18ms | -5.27
| getProfileImage | avg | 84ms | 80ms | -4ms | -4.78
| login | avg | 201ms | 192ms | -9ms | -4.47
| searchAllChannels | avg | 53ms | 51ms | -2ms | -3.79
| createPost | avg | 749ms | 740ms | -9ms | -1.20
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPlugins | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.00
| getProductNotices | p99 | 5ms | 0s | -5ms | -100.98
| deleteChannelBookmark | p99 | 50ms | 0s | -50ms | -100.50
| createJob | p99 | 50ms | 0s | -50ms | -100.50
| getUsersByGroupChannelIds | p99 | 10ms | 0s | -10ms | -100.49
| getConfig | p99 | 249ms | 0s | -249ms | -100.20
| searchFilesInTeam | p99 | 247ms | 0s | -247ms | -100.00
| channelMemberCountsByGroup | p99 | 31ms | 0s | -31ms | -98.41
| updateChannelBookmarkSortOrder | p99 | 98ms | 5ms | -93ms | -94.90
| getChannelMembers | p99 | 244ms | 98ms | -146ms | -59.84
| getServerLimits | p99 | 238ms | 99ms | -139ms | -58.40
| getJobsByType | p99 | 214ms | 90ms | -124ms | -57.94
| deletePost | p99 | 927ms | 447ms | -480ms | -51.75
| getGroups | p99 | 99ms | 50ms | -49ms | -49.49
| getFilteredUsersStats | p99 | 49ms | 25ms | -24ms | -49.23
| getAnalytics | p99 | 977ms | 498ms | -479ms | -49.00
| getTeamStats | p99 | 462ms | 237ms | -225ms | -48.65
| createSchedulePost | p99 | 275ms | 146ms | -129ms | -46.91
| getChannelMembersForUser | p99 | 150ms | 104ms | -46ms | -30.62
| getChannel | p99 | 321ms | 234ms | -87ms | -27.10
| unfollowThreadByUser | p99 | 680ms | 555ms | -125ms | -18.38
| getTeamsForUser | p99 | 151ms | 124ms | -27ms | -17.83
| getPostsForChannelAroundLastUnread | p99 | 573ms | 487ms | -86ms | -15.01
| getPreferences | p99 | 175ms | 149ms | -26ms | -14.86
| addTeamMember | p99 | 9.169s | 7.839s | -1.33s | -14.51
| getTeamMembersForUser | p99 | 170ms | 146ms | -24ms | -14.10
| getChannelMember | p99 | 273ms | 235ms | -38ms | -13.93
| getUserStatusesByIds | p99 | 109ms | 94ms | -15ms | -13.81
| listCPAFields | p99 | 179ms | 155ms | -24ms | -13.38
| getClientConfig | p99 | 278ms | 242ms | -36ms | -12.95
| getAllTeams | p99 | 185ms | 164ms | -21ms | -11.34
| login | p99 | 2.064s | 1.853s | -211ms | -10.23
| getUser | p99 | 266ms | 239ms | -27ms | -10.16
| setPostReminder | p99 | 855ms | 770ms | -85ms | -9.94
| createDirectChannel | p99 | 2.705s | 2.464s | -241ms | -8.91
| getUsersByIds | p99 | 58ms | 53ms | -5ms | -8.60
| getUsers | p99 | 248ms | 228ms | -20ms | -8.06
| getChannelsForUser | p99 | 138ms | 128ms | -10ms | -7.24
| getChannelStats | p99 | 169ms | 158ms | -11ms | -6.51
| createUser | p99 | 2.311s | 2.183s | -128ms | -5.54
| getCategoriesForTeamForUser | p99 | 226ms | 215ms | -11ms | -4.86
| getTeamScheduledPosts | p99 | 227ms | 216ms | -11ms | -4.86
| searchPostsInTeam | p99 | 2.313s | 2.245s | -68ms | -2.94
| searchAllChannels | p99 | 254ms | 249ms | -5ms | -1.97
| logout | p99 | 1.825s | 1.795s | -30ms | -1.64
| getProfileImage | p99 | 484ms | 477ms | -7ms | -1.45
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 8ms | -1ms | -11.026
| |  P99| 99ms| 93ms | -6ms | -6.062
| BotStore.Get |  Avg| 9ms| 17ms | 8ms | 89.452
| |  P99| 93ms| 210ms | 117ms | 126.486
| ChannelBookmarkStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 4ms| 11ms | 7ms | 157.036
| |  P99| 24ms| 49ms | 25ms | 105.041
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 174ms| 176ms | 2ms | 1.150
| ChannelBookmarkStore.Save |  Avg| 21ms| 65ms | 44ms | 213.671
| |  P99| 229ms| 455ms | 226ms | 98.690
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 25ms| 3ms | -22ms | -87.468
| |  P99| 97ms| 5ms | -92ms | -94.360
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring |  Avg| 68ms| 0s | -68ms | -100.221
| |  P99| 100ms| 0s | -100ms | -100.503
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 77ms| 71ms | -6ms | -7.749
| |  P99| 411ms| 238ms | -173ms | -42.105
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 6ms | -1ms | -14.420
| |  P99| 86ms| 70ms | -16ms | -18.606
| ChannelStore.AnalyticsCountAll |  Avg| 42ms| 46ms | 4ms | 9.599
| |  P99| 241ms| 99ms | -142ms | -58.921
| ChannelStore.Autocomplete |  Avg| 51ms| 51ms | 0s | 0.000
| |  P99| 246ms| 247ms | 1ms | 0.407
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 81ms| 132ms | 51ms | 63.108
| |  P99| 444ms| 3.271s | 2.827s | 636.713
| ChannelStore.CreateDirectChannel |  Avg| 83ms| 82ms | -1ms | -1.208
| |  P99| 798ms| 846ms | 48ms | 6.013
| ChannelStore.CreateInitialSidebarCategories |  Avg| 33ms| 27ms | -6ms | -18.174
| |  P99| 426ms| 350ms | -76ms | -17.823
| ChannelStore.CreateSidebarCategory |  Avg| 222ms| 149ms | -73ms | -32.847
| |  P99| 249ms| 970ms | 721ms | 290.141
| ChannelStore.Get |  Avg| 23ms| 26ms | 3ms | 13.016
| |  P99| 238ms| 339ms | 101ms | 42.350
| ChannelStore.GetAllChannelMembersForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 186ms| 191ms | 5ms | 2.688
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 30ms| 29ms | -1ms | -3.332
| |  P99| 375ms| 351ms | -24ms | -6.403
| ChannelStore.GetByName |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 140ms| 117ms | -23ms | -16.428
| ChannelStore.GetByNameIncludeDeleted |  Avg| 14ms| 0s | -14ms | -97.021
| |  P99| 96ms| 0s | -96ms | -99.482
| ChannelStore.GetChannelUnread |  Avg| 16ms| 18ms | 2ms | 12.764
| |  P99| 209ms| 247ms | 38ms | 18.204
| ChannelStore.GetChannels |  Avg| 16ms| 17ms | 1ms | 6.196
| |  P99| 212ms| 226ms | 14ms | 6.599
| ChannelStore.GetChannelsByUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 129ms| 122ms | -7ms | -5.436
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 13ms| 14ms | 1ms | 7.774
| |  P99| 185ms| 198ms | 13ms | 7.027
| ChannelStore.GetFileCount |  Avg| 15ms| 14ms | -1ms | -6.682
| |  P99| 200ms| 189ms | -11ms | -5.489
| ChannelStore.GetGuestCount |  Avg| 13ms| 12ms | -1ms | -7.731
| |  P99| 173ms| 146ms | -27ms | -15.650
| ChannelStore.GetMany |  Avg| 3ms| 0s | -3ms | -97.699
| |  P99| 5ms| 0s | -5ms | -100.973
| ChannelStore.GetMember |  Avg| 9ms| 8ms | -1ms | -10.809
| |  P99| 135ms| 100ms | -35ms | -25.865
| ChannelStore.GetMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 222ms| 219ms | -3ms | -1.348
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -98.117
| |  P99| 31ms| 0s | -31ms | -100.001
| ChannelStore.GetMemberForPost |  Avg| 20ms| 22ms | 2ms | 10.008
| |  P99| 222ms| 239ms | 17ms | 7.654
| ChannelStore.GetMemberLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 96ms | -3ms | -3.029
| ChannelStore.GetMembers |  Avg| 43ms| 17ms | -26ms | -60.033
| |  P99| 244ms| 49ms | -195ms | -79.918
| ChannelStore.GetMembersForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 207ms| 219ms | 12ms | 5.807
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 6ms| 26ms | 20ms | 312.693
| |  P99| 24ms| 49ms | 25ms | 103.093
| ChannelStore.GetMembersForUserWithPagination |  Avg| 11ms| 10ms | -1ms | -8.736
| |  P99| 142ms| 99ms | -43ms | -30.254
| ChannelStore.GetPinnedPostCount |  Avg| 13ms| 14ms | 1ms | 7.997
| |  P99| 183ms| 197ms | 14ms | 7.659
| ChannelStore.GetPublicChannelsForTeam |  Avg| 28ms| 32ms | 4ms | 14.089
| |  P99| 222ms| 238ms | 16ms | 7.220
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 18ms| 17ms | -1ms | -5.472
| |  P99| 220ms| 204ms | -16ms | -7.277
| ChannelStore.GetSidebarCategory |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 343ms| 450ms | 107ms | 31.240
| ChannelStore.GetTeamChannels |  Avg| 26ms| 40ms | 14ms | 53.891
| |  P99| 227ms| 223ms | -4ms | -1.758
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 8ms | -1ms | -10.994
| |  P99| 145ms| 120ms | -25ms | -17.235
| ChannelStore.Save |  Avg| 51ms| 55ms | 4ms | 7.838
| |  P99| 449ms| 494ms | 45ms | 10.028
| ChannelStore.SaveMember |  Avg| 65ms| 60ms | -5ms | -7.647
| |  P99| 580ms| 482ms | -98ms | -16.899
| ChannelStore.SearchGroupChannels |  Avg| 17ms| 19ms | 2ms | 11.577
| |  P99| 207ms| 229ms | 22ms | 10.631
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 138ms| 116ms | -22ms | -15.995
| ChannelStore.UpdateSidebarCategories |  Avg| 74ms| 97ms | 23ms | 31.254
| |  P99| 670ms| 1.57s | 900ms | 134.326
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 133ms| 115ms | -18ms | -13.568
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 21ms| 19ms | -2ms | -9.422
| |  P99| 216ms| 220ms | 4ms | 1.854
| CommandWebhookStore.Cleanup |  Avg| 35ms| 25ms | -10ms | -28.689
| |  P99| 98ms| 98ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 265ms| 563ms | 298ms | 112.429
| |  P99| 975ms| 995ms | 20ms | 2.051
| DraftStore.Delete |  Avg| 13ms| 12ms | -1ms | -7.653
| |  P99| 191ms| 149ms | -42ms | -21.982
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 15ms| 14ms | -1ms | -6.807
| |  P99| 86ms| 95ms | 9ms | 10.526
| DraftStore.Get |  Avg| 18ms| 20ms | 2ms | 11.086
| |  P99| 224ms| 243ms | 19ms | 8.495
| DraftStore.GetDraftsForUser |  Avg| 19ms| 20ms | 1ms | 5.298
| |  P99| 225ms| 248ms | 23ms | 10.211
| DraftStore.Upsert |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 199ms| 195ms | -4ms | -2.014
| EmojiStore.GetByName |  Avg| 12ms| 13ms | 1ms | 8.379
| |  P99| 170ms| 205ms | 35ms | 20.584
| EmojiStore.GetMultipleByName |  Avg| 35ms| 53ms | 18ms | 50.995
| |  P99| 239ms| 236ms | -3ms | -1.253
| EmojiStore.Search |  Avg| 2ms| 0s | -2ms | -96.124
| |  P99| 5ms| 0s | -5ms | -100.998
| FileInfoStore.AttachToPost |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 225ms| 226ms | 1ms | 0.445
| FileInfoStore.Get |  Avg| 14ms| 15ms | 1ms | 7.241
| |  P99| 198ms| 218ms | 20ms | 10.079
| FileInfoStore.GetByIds |  Avg| 14ms| 16ms | 2ms | 14.124
| |  P99| 207ms| 236ms | 29ms | 14.037
| FileInfoStore.GetForPost |  Avg| 12ms| 13ms | 1ms | 8.244
| |  P99| 183ms| 198ms | 15ms | 8.184
| FileInfoStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 200ms| 190ms | -10ms | -5.003
| FileInfoStore.Search |  Avg| 14ms| 0s | -14ms | -96.655
| |  P99| 25ms| 0s | -25ms | -101.215
| FileInfoStore.SetContent |  Avg| 22ms| 21ms | -1ms | -4.577
| |  P99| 241ms| 229ms | -12ms | -4.972
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 8ms| 7ms | -1ms | -12.449
| |  P99| 97ms| 85ms | -12ms | -12.422
| GroupStore.GetByName |  Avg| 9ms| 8ms | -1ms | -10.618
| |  P99| 124ms| 91ms | -33ms | -26.662
| GroupStore.GetGroups |  Avg| 12ms| 13ms | 1ms | 8.289
| |  P99| 164ms| 188ms | 24ms | 14.632
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 13ms | 11ms | 442.516
| |  P99| 5ms| 25ms | 20ms | 403.902
| JobStore.Get |  Avg| 18ms| 92ms | 74ms | 408.695
| |  P99| 97ms| 475ms | 378ms | 390.698
| JobStore.GetAllByStatus |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 207ms| 225ms | 18ms | 8.683
| JobStore.GetAllByTypePage |  Avg| 17ms| 8ms | -9ms | -53.566
| |  P99| 214ms| 90ms | -124ms | -57.945
| JobStore.GetAllByTypesAndStatusesPage |  Avg| 2ms| 0s | -2ms | -91.280
| |  P99| 5ms| 0s | -5ms | -100.973
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 25ms | 16ms | 173.477
| |  P99| 104ms| 227ms | 123ms | 117.703
| JobStore.GetNewestJobByStatusesAndType |  Avg| 7ms| 21ms | 14ms | 208.927
| |  P99| 87ms| 370ms | 283ms | 326.538
| JobStore.Save |  Avg| 7ms| 18ms | 11ms | 156.295
| |  P99| 79ms| 310ms | 231ms | 291.483
| JobStore.UpdateOptimistically |  Avg| 9ms| 11ms | 2ms | 22.917
| |  P99| 89ms| 195ms | 106ms | 118.548
| JobStore.UpdateStatus |  Avg| 10ms| 13ms | 3ms | 28.914
| |  P99| 90ms| 193ms | 103ms | 114.926
| JobStore.UpdateStatusOptimistically |  Avg| 15ms| 16ms | 1ms | 6.553
| |  P99| 208ms| 193ms | -15ms | -7.194
| LicenseStore.GetAll |  Avg| 12ms| 38ms | 26ms | 215.583
| |  P99| 49ms| 99ms | 50ms | 102.302
| LinkMetadataStore.Get |  Avg| 11ms| 12ms | 1ms | 9.055
| |  P99| 165ms| 195ms | 30ms | 18.217
| LinkMetadataStore.Save |  Avg| 7ms| 19ms | 12ms | 160.030
| |  P99| 65ms| 212ms | 147ms | 224.428
| PostAcknowledgementStore.GetForPost |  Avg| 10ms| 9ms | -1ms | -9.818
| |  P99| 97ms| 89ms | -8ms | -8.241
| PostAcknowledgementStore.GetForPosts |  Avg| 17ms| 19ms | 2ms | 11.850
| |  P99| 234ms| 250ms | 16ms | 6.836
| PostPersistentNotificationStore.DeleteExpired |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 89ms | -5ms | -5.340
| PostPersistentNotificationStore.Get |  Avg| 11ms| 13ms | 2ms | 18.802
| |  P99| 173ms| 183ms | 10ms | 5.764
| PostPersistentNotificationStore.GetSingle |  Avg| 9ms| 10ms | 1ms | 10.599
| |  P99| 137ms| 180ms | 43ms | 31.377
| PostPriorityStore.GetForPost |  Avg| 10ms| 11ms | 1ms | 9.525
| |  P99| 146ms| 145ms | -1ms | -0.683
| PostPriorityStore.GetForPosts |  Avg| 18ms| 20ms | 2ms | 11.385
| |  P99| 236ms| 258ms | 22ms | 9.336
| PostStore.AnalyticsPostCount |  Avg| 104ms| 302ms | 198ms | 190.542
| |  P99| 493ms| 985ms | 492ms | 99.897
| PostStore.AnalyticsPostCountByTeam |  Avg| 28ms| 22ms | -6ms | -21.521
| |  P99| 241ms| 99ms | -142ms | -58.921
| PostStore.Delete |  Avg| 53ms| 35ms | -18ms | -34.254
| |  P99| 427ms| 218ms | -209ms | -48.889
| PostStore.Get |  Avg| 32ms| 34ms | 2ms | 6.281
| |  P99| 343ms| 409ms | 66ms | 19.251
| PostStore.GetEtag |  Avg| 16ms| 15ms | -1ms | -6.431
| |  P99| 208ms| 215ms | 7ms | 3.358
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 5ms | -1ms | -16.806
| |  P99| 88ms| 75ms | -13ms | -14.706
| PostStore.GetPostIdBeforeTime |  Avg| 10ms| 7ms | -3ms | -30.621
| |  P99| 152ms| 96ms | -56ms | -36.803
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 16ms | 6ms | 60.775
| |  P99| 169ms| 115ms | -54ms | -31.954
| PostStore.GetPostReminders |  Avg| 15ms| 52ms | 37ms | 245.179
| |  P99| 227ms| 865ms | 638ms | 281.367
| PostStore.GetPosts |  Avg| 10ms| 9ms | -1ms | -10.371
| |  P99| 97ms| 92ms | -5ms | -5.152
| PostStore.GetPostsAfter |  Avg| 14ms| 15ms | 1ms | 7.154
| |  P99| 185ms| 199ms | 14ms | 7.587
| PostStore.GetPostsBefore |  Avg| 17ms| 18ms | 1ms | 5.919
| |  P99| 211ms| 220ms | 9ms | 4.272
| PostStore.GetPostsByThread |  Avg| 18ms| 21ms | 3ms | 16.359
| |  P99| 186ms| 212ms | 26ms | 13.953
| PostStore.GetPostsSince |  Avg| 27ms| 29ms | 2ms | 7.370
| |  P99| 228ms| 239ms | 11ms | 4.832
| PostStore.GetSingle |  Avg| 11ms| 12ms | 1ms | 9.326
| |  P99| 157ms| 191ms | 34ms | 21.700
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 37ms| 35ms | -2ms | -5.376
| |  P99| 438ms| 419ms | -19ms | -4.339
| PostStore.SearchPostsForUser |  Avg| 149ms| 152ms | 3ms | 2.018
| |  P99| 2.278s| 2.159s | -119ms | -5.223
| PostStore.SetPostReminder |  Avg| 38ms| 41ms | 3ms | 7.975
| |  P99| 855ms| 385ms | -470ms | -54.971
| PostStore.Update |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 408ms| 335ms | -73ms | -17.878
| PreferenceStore.DeleteCategoryAndName |  Avg| 11ms| 10ms | -1ms | -8.766
| |  P99| 93ms| 95ms | 2ms | 2.156
| PreferenceStore.Get |  Avg| 15ms| 16ms | 1ms | 6.712
| |  P99| 204ms| 218ms | 14ms | 6.860
| PreferenceStore.GetAll |  Avg| 12ms| 11ms | -1ms | -8.538
| |  P99| 161ms| 138ms | -23ms | -14.287
| PreferenceStore.Save |  Avg| 27ms| 25ms | -2ms | -7.297
| |  P99| 337ms| 272ms | -65ms | -19.298
| ProductNoticesStore.ClearOldNotices |  Avg| 35ms| 60ms | 25ms | 71.068
| |  P99| 50ms| 99ms | 49ms | 98.470
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 90ms| 75ms | -15ms | -16.738
| |  P99| 968ms| 836ms | -132ms | -13.630
| PropertyFieldStore.SearchPropertyFields |  Avg| 10ms| 9ms | -1ms | -10.035
| |  P99| 144ms| 108ms | -36ms | -24.938
| PropertyValueStore.SearchPropertyValues |  Avg| 15ms| 18ms | 3ms | 20.297
| |  P99| 206ms| 231ms | 25ms | 12.146
| ReactionStore.GetForPost |  Avg| 13ms| 14ms | 1ms | 7.426
| |  P99| 181ms| 188ms | 7ms | 3.867
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -103.801
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 57ms| 0s | -57ms | -100.181
| |  P99| 247ms| 0s | -247ms | -100.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 44ms| 63ms | 19ms | 42.731
| |  P99| 439ms| 492ms | 53ms | 12.085
| RoleStore.GetByNames |  Avg| 63ms| 79ms | 16ms | 25.484
| |  P99| 473ms| 830ms | 357ms | 75.423
| ScheduledPostStore.CreateScheduledPost |  Avg| 10ms| 12ms | 2ms | 19.262
| |  P99| 182ms| 146ms | -36ms | -19.726
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 13ms| 29ms | 16ms | 126.927
| |  P99| 203ms| 230ms | 27ms | 13.268
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 104ms| 96ms | -8ms | -7.724
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 5ms| 17ms | 12ms | 259.309
| |  P99| 84ms| 210ms | 126ms | 149.112
| SchemeStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 19ms| 17ms | -2ms | -10.260
| |  P99| 231ms| 217ms | -14ms | -6.055
| SessionStore.GetLRUSessions |  Avg| 9ms| 8ms | -1ms | -11.570
| |  P99| 99ms| 94ms | -5ms | -5.025
| SessionStore.GetSessionsExpired |  Avg| 15ms| 11ms | -4ms | -27.236
| |  P99| 94ms| 47ms | -47ms | -50.001
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 12ms| 13ms | 1ms | 8.170
| |  P99| 169ms| 186ms | 17ms | 10.033
| SessionStore.Remove |  Avg| 12ms| 10ms | -2ms | -17.108
| |  P99| 89ms| 180ms | 91ms | 102.535
| SessionStore.Save |  Avg| 16ms| 15ms | -1ms | -6.177
| |  P99| 205ms| 180ms | -25ms | -12.211
| SessionStore.UpdateLastActivityAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 113ms| 100ms | -13ms | -11.512
| StatusStore.Get |  Avg| 12ms| 11ms | -1ms | -8.577
| |  P99| 168ms| 170ms | 2ms | 1.187
| StatusStore.GetByIds |  Avg| 20ms| 21ms | 1ms | 5.083
| |  P99| 227ms| 242ms | 15ms | 6.608
| StatusStore.SaveOrUpdate |  Avg| 13ms| 12ms | -1ms | -7.866
| |  P99| 177ms| 170ms | -7ms | -3.953
| StatusStore.SaveOrUpdateMany |  Avg| 19ms| 18ms | -1ms | -5.330
| |  P99| 214ms| 221ms | 7ms | 3.278
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 10ms| 15ms | 5ms | 48.546
| |  P99| 130ms| 198ms | 68ms | 52.308
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 9ms | -1ms | -10.390
| |  P99| 118ms| 103ms | -15ms | -12.670
| SystemStore.GetByName |  Avg| 7ms| 6ms | -1ms | -14.000
| |  P99| 99ms| 92ms | -7ms | -7.041
| TeamStore.AnalyticsTeamCount |  Avg| 13ms| 34ms | 21ms | 160.071
| |  P99| 48ms| 98ms | 50ms | 103.093
| TeamStore.Get |  Avg| 10ms| 11ms | 1ms | 9.888
| |  P99| 147ms| 181ms | 34ms | 23.183
| TeamStore.GetActiveMemberCount |  Avg| 84ms| 62ms | -22ms | -26.308
| |  P99| 462ms| 237ms | -225ms | -48.649
| TeamStore.GetAllPage |  Avg| 10ms| 9ms | -1ms | -9.727
| |  P99| 144ms| 110ms | -34ms | -23.686
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 11ms| 10ms | -1ms | -9.335
| |  P99| 144ms| 124ms | -20ms | -13.872
| TeamStore.GetMember |  Avg| 7ms| 6ms | -1ms | -14.032
| |  P99| 93ms| 84ms | -9ms | -9.696
| TeamStore.GetTeamsByUserId |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 141ms| 113ms | -28ms | -19.823
| TeamStore.GetTeamsForUser |  Avg| 10ms| 9ms | -1ms | -9.899
| |  P99| 134ms| 100ms | -34ms | -25.385
| TeamStore.GetTotalMemberCount |  Avg| 64ms| 52ms | -12ms | -18.852
| |  P99| 239ms| 223ms | -16ms | -6.702
| TeamStore.SaveMember |  Avg| 36ms| 33ms | -3ms | -8.343
| |  P99| 241ms| 229ms | -12ms | -4.978
| ThreadStore.Get |  Avg| 8ms| 10ms | 2ms | 24.789
| |  P99| 79ms| 98ms | 19ms | 23.950
| ThreadStore.GetMembershipForUser |  Avg| 13ms| 14ms | 1ms | 7.983
| |  P99| 188ms| 210ms | 22ms | 11.677
| ThreadStore.GetTeamsUnreadForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 199ms| 201ms | 2ms | 1.004
| ThreadStore.GetThreadFollowers |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 131ms| 177ms | 46ms | 35.095
| ThreadStore.GetThreadForUser |  Avg| 22ms| 23ms | 1ms | 4.609
| |  P99| 238ms| 246ms | 8ms | 3.365
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 21ms| 23ms | 2ms | 9.340
| |  P99| 204ms| 220ms | 16ms | 7.854
| ThreadStore.GetThreadsForUser |  Avg| 18ms| 20ms | 2ms | 10.987
| |  P99| 217ms| 233ms | 16ms | 7.358
| ThreadStore.GetTotalThreads |  Avg| 11ms| 10ms | -1ms | -9.471
| |  P99| 147ms| 143ms | -4ms | -2.712
| ThreadStore.GetTotalUnreadMentions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 162ms| 165ms | 3ms | 1.854
| ThreadStore.GetTotalUnreadThreads |  Avg| 11ms| 10ms | -1ms | -9.482
| |  P99| 143ms| 135ms | -8ms | -5.594
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 153ms| 143ms | -10ms | -6.556
| ThreadStore.MaintainMembership |  Avg| 20ms| 19ms | -1ms | -5.051
| |  P99| 247ms| 244ms | -3ms | -1.215
| ThreadStore.MarkAllAsReadByChannels |  Avg| 13ms| 11ms | -2ms | -15.714
| |  P99| 183ms| 136ms | -47ms | -25.643
| ThreadStore.MarkAllAsReadByTeam |  Avg| 7ms| 8ms | 1ms | 13.792
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 10ms| 9ms | -1ms | -10.512
| |  P99| 100ms| 99ms | -1ms | -1.003
| ThreadStore.UpdateMembership |  Avg| 10ms| 9ms | -1ms | -10.396
| |  P99| 106ms| 99ms | -7ms | -6.626
| TokenStore.Cleanup |  Avg| 22ms| 36ms | 14ms | 64.394
| |  P99| 49ms| 244ms | 195ms | 397.959
| UserAccessTokenStore.GetByToken |  Avg| 11ms| 9ms | -2ms | -18.418
| |  P99| 92ms| 92ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 39ms| 37ms | -2ms | -5.068
| |  P99| 232ms| 97ms | -135ms | -58.190
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 36ms | 34ms | 1492.002
| |  P99| 5ms| 99ms | 94ms | 1898.990
| UserStore.AutocompleteUsersInChannel |  Avg| 69ms| 73ms | 4ms | 5.797
| |  P99| 383ms| 428ms | 45ms | 11.753
| UserStore.Count |  Avg| 25ms| 24ms | -1ms | -4.051
| |  P99| 190ms| 181ms | -9ms | -4.739
| UserStore.Get |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 181ms| 186ms | 5ms | 2.755
| UserStore.GetAllProfiles |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 87ms | -5ms | -5.407
| UserStore.GetAllProfilesInChannel |  Avg| 356ms| 338ms | -18ms | -5.054
| |  P99| 2.149s| 2.02s | -129ms | -6.003
| UserStore.GetByUsername |  Avg| 16ms| 18ms | 2ms | 12.748
| |  P99| 208ms| 227ms | 19ms | 9.125
| UserStore.GetForLogin |  Avg| 10ms| 9ms | -1ms | -9.869
| |  P99| 136ms| 99ms | -37ms | -27.177
| UserStore.GetMany |  Avg| 12ms| 10ms | -2ms | -16.074
| |  P99| 199ms| 92ms | -107ms | -53.770
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 5ms| 4ms | -1ms | -20.592
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 14ms| 15ms | 1ms | 6.943
| |  P99| 204ms| 214ms | 10ms | 4.895
| UserStore.GetProfilesByUsernames |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 210ms| 215ms | 5ms | 2.377
| UserStore.GetProfilesInChannel |  Avg| 35ms| 30ms | -5ms | -14.490
| |  P99| 241ms| 450ms | 209ms | 86.902
| UserStore.GetProfilesNotInChannel |  Avg| 14ms| 13ms | -1ms | -7.185
| |  P99| 92ms| 91ms | -1ms | -1.081
| UserStore.GetUnreadCount |  Avg| 12ms| 13ms | 1ms | 8.221
| |  P99| 177ms| 199ms | 22ms | 12.397
| UserStore.IsEmpty |  Avg| 5ms| 4ms | -1ms | -21.451
| |  P99| 59ms| 49ms | -10ms | -17.078
| UserStore.Save |  Avg| 176ms| 175ms | -1ms | -0.568
| |  P99| 737ms| 522ms | -215ms | -29.165
| UserStore.Search |  Avg| 49ms| 50ms | 1ms | 2.049
| |  P99| 243ms| 248ms | 5ms | 2.058
| UserStore.Update |  Avg| 30ms| 34ms | 4ms | 13.265
| |  P99| 233ms| 363ms | 130ms | 55.807
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 99ms| 93ms | -6ms | -6.054
| UserStore.UpdateLastLogin |  Avg| 9ms| 8ms | -1ms | -11.451
| |  P99| 91ms| 80ms | -11ms | -12.143
| UserStore.UpdateUpdateAt |  Avg| 9ms| 8ms | -1ms | -11.706
| |  P99| 88ms| 77ms | -11ms | -12.541
| UserTermsOfServiceStore.GetByUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 117ms| 99ms | -18ms | -15.396
| WebhookStore.GetOutgoingByTeam |  Avg| 18ms| 19ms | 1ms | 5.682
| |  P99| 217ms| 231ms | 14ms | 6.456
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 498ms| 536ms | 38ms | 7.625
| | P99| 3.471s| 4.525s | 1.054s | 30.368
| addTeamMember | Avg| 1.384s| 1.233s | -151ms | -10.911
| | P99| 9.169s| 7.839s | -1.33s | -14.506
| autocompleteChannelsForTeamForSearch | Avg| 81ms| 132ms | 51ms | 62.883
| | P99| 444ms| 3.271s | 2.827s | 636.713
| autocompleteEmojis | Avg| 2ms| 0s | -2ms | -93.611
| | P99| 5ms| 0s | -5ms | -100.998
| autocompleteUsers | Avg| 65ms| 70ms | 5ms | 7.691
| | P99| 396ms| 448ms | 52ms | 13.125
| channelMemberCountsByGroup | Avg| 4ms| 0s | -4ms | -90.306
| | P99| 31ms| 0s | -31ms | -98.413
| createCategoryForTeamForUser | Avg| 245ms| 175ms | -70ms | -28.551
| | P99| 495ms| 970ms | 475ms | 95.960
| createChannel | Avg| 318ms| 423ms | 105ms | 32.986
| | P99| 925ms| 2.365s | 1.44s | 155.676
| createChannelBookmark | Avg| 35ms| 94ms | 59ms | 166.436
| | P99| 234ms| 935ms | 701ms | 300.213
| createDirectChannel | Avg| 548ms| 495ms | -53ms | -9.676
| | P99| 2.705s| 2.464s | -241ms | -8.910
| createGroupChannel | Avg| 865ms| 974ms | 109ms | 12.594
| | P99| 4.525s| 7.387s | 2.862s | 63.249
| createJob | Avg| 26ms| 0s | -26ms | -101.928
| | P99| 50ms| 0s | -50ms | -100.503
| createPost | Avg| 749ms| 740ms | -9ms | -1.202
| | P99| 4.962s| 5.818s | 856ms | 17.252
| createSchedulePost | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 275ms| 146ms | -129ms | -46.911
| createUser | Avg| 398ms| 373ms | -25ms | -6.278
| | P99| 2.311s| 2.183s | -128ms | -5.539
| deleteChannelBookmark | Avg| 31ms| 0s | -31ms | -101.049
| | P99| 50ms| 0s | -50ms | -100.503
| deleteDraft | Avg| 19ms| 21ms | 2ms | 10.463
| | P99| 230ms| 247ms | 17ms | 7.381
| deletePost | Avg| 104ms| 58ms | -46ms | -44.274
| | P99| 927ms| 447ms | -480ms | -51.752
| followThreadByUser | Avg| 51ms| 64ms | 13ms | 25.718
| | P99| 425ms| 800ms | 375ms | 88.234
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 12ms| 11ms | -1ms | -8.216
| | P99| 185ms| 164ms | -21ms | -11.336
| getAnalytics | Avg| 254ms| 374ms | 120ms | 47.248
| | P99| 977ms| 498ms | -479ms | -49.003
| getCategoriesForTeamForUser | Avg| 19ms| 18ms | -1ms | -5.197
| | P99| 226ms| 215ms | -11ms | -4.860
| getChannel | Avg| 28ms| 23ms | -5ms | -17.847
| | P99| 321ms| 234ms | -87ms | -27.103
| getChannelMember | Avg| 22ms| 20ms | -2ms | -9.066
| | P99| 273ms| 235ms | -38ms | -13.926
| getChannelMembers | Avg| 44ms| 27ms | -17ms | -38.751
| | P99| 244ms| 98ms | -146ms | -59.836
| getChannelMembersForTeamForUser | Avg| 16ms| 17ms | 1ms | 6.247
| | P99| 210ms| 223ms | 13ms | 6.178
| getChannelMembersForUser | Avg| 12ms| 11ms | -1ms | -8.489
| | P99| 150ms| 104ms | -46ms | -30.617
| getChannelStats | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 169ms| 158ms | -11ms | -6.513
| getChannelUnread | Avg| 18ms| 21ms | 3ms | 17.096
| | P99| 230ms| 353ms | 123ms | 53.523
| getChannelsForTeamForUser | Avg| 17ms| 18ms | 1ms | 6.039
| | P99| 216ms| 230ms | 14ms | 6.482
| getChannelsForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 138ms| 128ms | -10ms | -7.237
| getClientConfig | Avg| 22ms| 18ms | -4ms | -18.530
| | P99| 278ms| 242ms | -36ms | -12.953
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 129ms| 0s | -129ms | -100.076
| | P99| 249ms| 0s | -249ms | -100.201
| getDrafts | Avg| 20ms| 21ms | 1ms | 4.894
| | P99| 233ms| 272ms | 39ms | 16.712
| getFilePreview | Avg| 71ms| 73ms | 2ms | 2.827
| | P99| 447ms| 473ms | 26ms | 5.818
| getFileThumbnail | Avg| 64ms| 67ms | 3ms | 4.693
| | P99| 422ms| 454ms | 32ms | 7.590
| getFilteredUsersStats | Avg| 17ms| 19ms | 2ms | 11.850
| | P99| 49ms| 25ms | -24ms | -49.229
| getGroups | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 99ms| 50ms | -49ms | -49.495
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 24ms | 22ms | 897.037
| | P99| 5ms| 25ms | 20ms | 404.040
| getJobsByType | Avg| 18ms| 8ms | -10ms | -57.074
| | P99| 214ms| 90ms | -124ms | -57.945
| getPlugins | Avg| 1ms| 0s | -1ms | -163.189
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 75ms| 86ms | 11ms | 14.631
| | P99| 752ms| 981ms | 229ms | 30.435
| getPostsForChannel | Avg| 128ms| 142ms | 14ms | 10.940
| | P99| 1.757s| 2.055s | 298ms | 16.963
| getPostsForChannelAroundLastUnread | Avg| 55ms| 52ms | -3ms | -5.481
| | P99| 573ms| 487ms | -86ms | -15.014
| getPreferences | Avg| 12ms| 11ms | -1ms | -8.133
| | P99| 175ms| 149ms | -26ms | -14.855
| getPrevTrialLicense | Avg| 12ms| 77ms | 65ms | 539.479
| | P99| 49ms| 100ms | 51ms | 104.082
| getProductNotices | Avg| 3ms| 0s | -3ms | -115.033
| | P99| 5ms| 0s | -5ms | -100.975
| getProfileImage | Avg| 84ms| 80ms | -4ms | -4.778
| | P99| 484ms| 477ms | -7ms | -1.446
| getPublicChannelsForTeam | Avg| 30ms| 34ms | 4ms | 13.526
| | P99| 222ms| 238ms | 16ms | 7.220
| getRolesByNames | Avg| 5ms| 17ms | 12ms | 224.745
| | P99| 10ms| 98ms | 88ms | 884.422
| getServerLimits | Avg| 36ms| 58ms | 22ms | 60.417
| | P99| 238ms| 99ms | -139ms | -58.403
| getTeamMember | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 184ms| 199ms | 15ms | 8.139
| getTeamMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 170ms| 146ms | -24ms | -14.096
| getTeamScheduledPosts | Avg| 19ms| 18ms | -1ms | -5.291
| | P99| 227ms| 216ms | -11ms | -4.856
| getTeamStats | Avg| 91ms| 65ms | -26ms | -28.429
| | P99| 462ms| 237ms | -225ms | -48.649
| getTeamsForUser | Avg| 11ms| 10ms | -1ms | -9.317
| | P99| 151ms| 124ms | -27ms | -17.832
| getTeamsUnreadForUser | Avg| 20ms| 19ms | -1ms | -5.000
| | P99| 238ms| 236ms | -2ms | -0.839
| getThreadsForUser | Avg| 18ms| 19ms | 1ms | 5.466
| | P99| 223ms| 236ms | 13ms | 5.818
| getUser | Avg| 19ms| 17ms | -2ms | -10.750
| | P99| 266ms| 239ms | -27ms | -10.161
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 109ms| 94ms | -15ms | -13.812
| getUsers | Avg| 17ms| 15ms | -2ms | -11.883
| | P99| 248ms| 228ms | -20ms | -8.057
| getUsersByGroupChannelIds | Avg| 5ms| 0s | -5ms | -93.900
| | P99| 10ms| 0s | -10ms | -100.485
| getUsersByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 58ms| 53ms | -5ms | -8.604
| getUsersByNames | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 216ms| 221ms | 5ms | 2.315
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 83ms| 168ms | 85ms | 102.618
| | P99| 100ms| 249ms | 149ms | 149.732
| listCPAFields | Avg| 12ms| 10ms | -2ms | -17.326
| | P99| 179ms| 155ms | -24ms | -13.380
| listCPAValues | Avg| 15ms| 19ms | 4ms | 25.830
| | P99| 210ms| 241ms | 31ms | 14.730
| listChannelBookmarksForChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 199ms| 200ms | 1ms | 0.502
| login | Avg| 201ms| 192ms | -9ms | -4.470
| | P99| 2.064s| 1.853s | -211ms | -10.225
| logout | Avg| 159ms| 141ms | -18ms | -11.286
| | P99| 1.825s| 1.795s | -30ms | -1.644
| patchPost | Avg| 101ms| 122ms | 21ms | 20.720
| | P99| 922ms| 1.255s | 333ms | 36.112
| removeUserCustomStatus | Avg| 341ms| 323ms | -18ms | -5.271
| | P99| 2.231s| 2.311s | 80ms | 3.585
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 46ms| 51ms | 5ms | 10.834
| | P99| 456ms| 595ms | 139ms | 30.464
| searchAllChannels | Avg| 53ms| 51ms | -2ms | -3.786
| | P99| 254ms| 249ms | -5ms | -1.970
| searchFilesInTeam | Avg| 73ms| 0s | -73ms | -100.173
| | P99| 247ms| 0s | -247ms | -100.000
| searchGroupChannels | Avg| 18ms| 20ms | 2ms | 11.353
| | P99| 210ms| 231ms | 21ms | 9.993
| searchPostsInTeam | Avg| 180ms| 186ms | 6ms | 3.324
| | P99| 2.313s| 2.245s | -68ms | -2.940
| searchUsers | Avg| 51ms| 52ms | 1ms | 1.960
| | P99| 245ms| 252ms | 7ms | 2.854
| setPostReminder | Avg| 84ms| 97ms | 13ms | 15.396
| | P99| 855ms| 770ms | -85ms | -9.942
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 50ms| 68ms | 18ms | 36.166
| | P99| 680ms| 555ms | -125ms | -18.382
| updateCategoriesForTeamForUser | Avg| 142ms| 169ms | 27ms | 18.954
| | P99| 1.525s| 3.45s | 1.925s | 126.226
| updateChannelBookmark | Avg| 32ms| 42ms | 10ms | 31.390
| | P99| 50ms| 98ms | 48ms | 96.482
| updateChannelBookmarkSortOrder | Avg| 28ms| 3ms | -25ms | -89.100
| | P99| 98ms| 5ms | -93ms | -94.898
| updatePreferences | Avg| 42ms| 42ms | 0s | 0.000
| | P99| 454ms| 474ms | 20ms | 4.407
| updateReadStateAllThreadsByUser | Avg| 7ms| 9ms | 2ms | 27.200
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 153ms| 168ms | 15ms | 9.791
| | P99| 1.203s| 1.906s | 703ms | 58.442
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 649.901
| | P99| 5ms| 12ms | 7ms | 140.750
| uploadFileStream | Avg| 555ms| 557ms | 2ms | 0.360
| | P99| 2.308s| 2.29s | -18ms | -0.780
| upsertDraft | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 236ms| 238ms | 2ms | 0.848
| viewChannel | Avg| 55ms| 57ms | 2ms | 3.635
| | P99| 631ms| 701ms | 70ms | 11.085
