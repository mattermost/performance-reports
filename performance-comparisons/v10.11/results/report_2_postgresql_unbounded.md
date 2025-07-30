### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 2ms | 48ms | 46ms | 2405.26
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 19ms | 15ms | 356.76
| LicenseStore.GetAll | avg | 1ms | 5ms | 4ms | 303.66
| CommandWebhookStore.Cleanup | avg | 14ms | 52ms | 38ms | 270.18
| RoleStore.GetByNames | avg | 6ms | 19ms | 13ms | 202.97
| PreferenceStore.DeleteCategoryAndName | avg | 6ms | 18ms | 12ms | 186.47
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 64ms | 157ms | 93ms | 144.91
| EmojiStore.GetMultipleByName | avg | 3ms | 6ms | 3ms | 111.21
| PluginStore.List | avg | 7ms | 13ms | 6ms | 86.82
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 12ms | 18ms | 6ms | 51.92
| BotStore.Get | avg | 10ms | 14ms | 4ms | 40.59
| PostStore.AnalyticsPostCount | avg | 289ms | 392ms | 103ms | 35.70
| UserStore.Update | avg | 17ms | 23ms | 6ms | 34.29
| PostPriorityStore.GetForPost | avg | 6ms | 8ms | 2ms | 34.12
| ScheduledPostStore.GetPendingScheduledPosts | avg | 12ms | 16ms | 4ms | 33.85
| ChannelBookmarkStore.Save | avg | 15ms | 20ms | 5ms | 33.20
| UserStore.GetProfilesNotInChannel | avg | 17ms | 22ms | 5ms | 30.17
| ChannelStore.Save | avg | 37ms | 48ms | 11ms | 29.63
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 12ms | 15ms | 3ms | 24.68
| UserAccessTokenStore.GetByToken | avg | 9ms | 11ms | 2ms | 23.28
| ProductNoticesStore.ClearOldNotices | avg | 25ms | 30ms | 5ms | 19.72
| ChannelStore.GetTeamChannels | avg | 42ms | 48ms | 6ms | 14.43
| PostStore.SearchPostsForUser | avg | 152ms | 158ms | 6ms | 3.95
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | p99 | 5ms | 244ms | 239ms | 4827.66
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 49ms | 44ms | 888.80
| LicenseStore.GetAll | p99 | 5ms | 25ms | 20ms | 404.04
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 100ms | 493ms | 393ms | 394.97
| PreferenceStore.DeleteCategoryAndName | p99 | 44ms | 214ms | 170ms | 383.96
| BotStore.Get | p99 | 93ms | 428ms | 335ms | 360.22
| RoleStore.GetByNames | p99 | 82ms | 215ms | 133ms | 161.70
| CommandWebhookStore.Cleanup | p99 | 98ms | 244ms | 146ms | 148.98
| ChannelBookmarkStore.Save | p99 | 96ms | 228ms | 132ms | 137.74
| UserStore.GetProfilesNotInChannel | p99 | 96ms | 211ms | 115ms | 119.58
| PostStore.AnalyticsPostCount | p99 | 498ms | 990ms | 492ms | 98.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 93ms | 170ms | 77ms | 83.02
| ChannelStore.GetTeamChannels | p99 | 238ms | 435ms | 197ms | 82.60
| UserAccessTokenStore.GetByToken | p99 | 87ms | 157ms | 70ms | 80.00
| PostStore.GetPostReminderMetadata | p99 | 92ms | 140ms | 48ms | 52.39
| ChannelStore.Save | p99 | 325ms | 477ms | 152ms | 46.77
| PostStore.Update | p99 | 233ms | 320ms | 87ms | 37.33
| PluginStore.List | p99 | 72ms | 95ms | 23ms | 31.94
| PostPriorityStore.GetForPost | p99 | 71ms | 88ms | 17ms | 23.83
| UserStore.Update | p99 | 202ms | 230ms | 28ms | 13.86
| FileInfoStore.Save | p99 | 150ms | 170ms | 20ms | 13.29
| UserStore.GetByUsername | p99 | 172ms | 185ms | 13ms | 7.56
| PostStore.SearchPostsForUser | p99 | 2.28s | 2.344s | 64ms | 2.81
| ChannelStore.Autocomplete | p99 | 236ms | 240ms | 4ms | 1.69
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | avg | 3ms | 0s | -3ms | -118.45
| ChannelStore.GetByNameIncludeDeleted | avg | 5ms | 0s | -5ms | -102.57
| ChannelStore.GetMemberCountsByGroup | avg | 18ms | 0s | -18ms | -102.39
| PluginStore.Delete | avg | 5ms | 0s | -5ms | -99.40
| EmojiStore.Search | avg | 34ms | 0s | -34ms | -99.28
| PluginStore.SetWithOptions | avg | 11ms | 0s | -11ms | -97.23
| PluginStore.Get | avg | 3ms | 0s | -3ms | -94.61
| DesktopTokensStore.DeleteOlderThan | avg | 2ms | 0s | -2ms | -94.32
| ProductNoticesStore.GetViews | avg | 46ms | 8ms | -38ms | -83.38
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 53ms | 12ms | -41ms | -77.69
| ChannelBookmarkStore.Get | avg | 17ms | 4ms | -13ms | -75.61
| SessionStore.GetSessionsExpired | avg | 13ms | 4ms | -9ms | -69.98
| ChannelStore.GetMembers | avg | 19ms | 6ms | -13ms | -69.03
| PostPersistentNotificationStore.Get | avg | 9ms | 3ms | -6ms | -64.81
| PostStore.AnalyticsPostCountByTeam | avg | 5ms | 2ms | -3ms | -58.56
| StatusStore.SaveOrUpdate | avg | 26ms | 11ms | -15ms | -57.31
| PostPersistentNotificationStore.DeleteExpired | avg | 7ms | 3ms | -4ms | -56.11
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 31ms | 14ms | -17ms | -54.91
| ChannelBookmarkStore.UpdateSortOrder | avg | 15ms | 7ms | -8ms | -52.39
| UserStore.GetProfilesInChannel | avg | 26ms | 13ms | -13ms | -49.54
| ChannelStore.AutocompleteInTeamForSearch | avg | 76ms | 41ms | -35ms | -46.31
| ChannelStore.UpdateSidebarCategories | avg | 133ms | 75ms | -58ms | -43.66
| TeamStore.AnalyticsTeamCount | avg | 7ms | 4ms | -3ms | -43.06
| UserStore.AnalyticsGetInactiveUsersCount | avg | 17ms | 10ms | -7ms | -42.25
| JobStore.UpdateStatusOptimistically | avg | 11ms | 7ms | -4ms | -37.73
| JobStore.UpdateStatus | avg | 14ms | 9ms | -5ms | -37.01
| ChannelStore.CreateInitialSidebarCategories | avg | 43ms | 29ms | -14ms | -32.61
| JobStore.Save | avg | 13ms | 9ms | -4ms | -30.68
| ChannelStore.AnalyticsCountAll | avg | 37ms | 26ms | -11ms | -29.59
| TeamStore.Get | avg | 8ms | 6ms | -2ms | -25.45
| LinkMetadataStore.Get | avg | 9ms | 7ms | -2ms | -22.61
| JobStore.UpdateOptimistically | avg | 9ms | 7ms | -2ms | -22.55
| LinkMetadataStore.Save | avg | 9ms | 7ms | -2ms | -22.33
| ChannelStore.GetSidebarCategory | avg | 32ms | 25ms | -7ms | -22.12
| PropertyValueStore.SearchPropertyValues | avg | 14ms | 11ms | -3ms | -21.69
| TeamStore.GetTotalMemberCount | avg | 70ms | 55ms | -15ms | -21.55
| PostStore.Delete | avg | 42ms | 33ms | -9ms | -21.30
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 14ms | 11ms | -3ms | -20.92
| FileInfoStore.GetForPost | avg | 10ms | 8ms | -2ms | -20.83
| PostStore.SetPostReminder | avg | 40ms | 33ms | -7ms | -17.53
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 23ms | 19ms | -4ms | -17.12
| ThreadStore.MaintainMembership | avg | 18ms | 15ms | -3ms | -17.01
| PostStore.GetPostsAfter | avg | 12ms | 10ms | -2ms | -16.70
| TeamStore.GetActiveMemberCount | avg | 79ms | 66ms | -13ms | -16.39
| PostStore.GetEtag | avg | 13ms | 11ms | -2ms | -15.90
| UserStore.GetProfileByIds | avg | 13ms | 11ms | -2ms | -15.67
| PostAcknowledgementStore.GetForPosts | avg | 13ms | 11ms | -2ms | -15.44
| ChannelStore.GetChannels | avg | 14ms | 12ms | -2ms | -14.71
| PostPriorityStore.GetForPosts | avg | 14ms | 12ms | -2ms | -14.63
| ChannelStore.CreateDirectChannel | avg | 77ms | 66ms | -11ms | -14.35
| SessionStore.Remove | avg | 14ms | 12ms | -2ms | -14.27
| JobStore.GetCountByStatusAndType | avg | 14ms | 12ms | -2ms | -14.14
| PostStore.GetPostsBefore | avg | 15ms | 13ms | -2ms | -13.77
| DraftStore.GetDraftsForUser | avg | 15ms | 13ms | -2ms | -13.74
| DraftStore.Get | avg | 15ms | 13ms | -2ms | -13.38
| JobStore.GetAllByStatus | avg | 15ms | 13ms | -2ms | -13.14
| ClusterDiscoveryStore.SetLastPingAt | avg | 16ms | 14ms | -2ms | -12.81
| ThreadStore.GetThreadsForUser | avg | 16ms | 14ms | -2ms | -12.79
| ChannelStore.GetPublicChannelsForTeam | avg | 32ms | 28ms | -4ms | -12.64
| ChannelStore.SearchGroupChannels | avg | 16ms | 14ms | -2ms | -12.63
| FileInfoStore.AttachToPost | avg | 17ms | 15ms | -2ms | -12.12
| StatusStore.GetByIds | avg | 17ms | 15ms | -2ms | -11.94
| PostStore.GetPostReminders | avg | 25ms | 22ms | -3ms | -11.78
| ThreadStore.GetThreadForUser | avg | 18ms | 16ms | -2ms | -10.95
| ChannelStore.Get | avg | 18ms | 16ms | -2ms | -10.84
| ChannelBookmarkStore.Delete | avg | 19ms | 17ms | -2ms | -10.72
| PostStore.Save | avg | 33ms | 30ms | -3ms | -9.06
| ProductNoticesStore.View | avg | 69ms | 63ms | -6ms | -8.72
| ChannelStore.SaveMember | avg | 58ms | 53ms | -5ms | -8.62
| PreferenceStore.Save | avg | 25ms | 23ms | -2ms | -8.02
| ChannelStore.GetMemberCount | avg | 39ms | 36ms | -3ms | -7.61
| PostStore.Get | avg | 27ms | 25ms | -2ms | -7.33
| TeamStore.SaveMember | avg | 42ms | 39ms | -3ms | -7.20
| UserStore.GetAllProfilesInChannel | avg | 334ms | 319ms | -15ms | -4.49
| UserStore.Save | avg | 92ms | 90ms | -2ms | -2.18
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | p99 | 25ms | 0s | -25ms | -101.83
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -100.96
| FileInfoStore.Search | p99 | 5ms | 0s | -5ms | -100.93
| EmojiStore.Search | p99 | 99ms | 0s | -99ms | -99.95
| PluginStore.SetWithOptions | p99 | 140ms | 0s | -140ms | -99.85
| ChannelStore.GetMemberCountsByGroup | p99 | 212ms | 0s | -212ms | -99.77
| PluginStore.Delete | p99 | 66ms | 0s | -66ms | -99.51
| PluginStore.Get | p99 | 22ms | 0s | -22ms | -98.65
| SessionStore.GetSessionsExpired | p99 | 233ms | 23ms | -210ms | -89.94
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 245ms | 25ms | -220ms | -89.61
| ProductNoticesStore.GetViews | p99 | 245ms | 25ms | -220ms | -89.61
| ChannelBookmarkStore.Get | p99 | 231ms | 24ms | -207ms | -89.51
| PostStore.AnalyticsPostCountByTeam | p99 | 25ms | 5ms | -20ms | -81.47
| ChannelBookmarkStore.UpdateSortOrder | p99 | 49ms | 10ms | -39ms | -79.57
| ChannelStore.GetMembers | p99 | 49ms | 10ms | -39ms | -78.99
| StatusStore.SaveOrUpdate | p99 | 401ms | 115ms | -286ms | -71.39
| ChannelStore.UpdateSidebarCategories | p99 | 1.39s | 467ms | -923ms | -66.41
| TeamStore.AnalyticsTeamCount | p99 | 25ms | 10ms | -15ms | -61.10
| JobStore.UpdateStatus | p99 | 221ms | 90ms | -131ms | -59.14
| PostPersistentNotificationStore.Get | p99 | 88ms | 38ms | -50ms | -56.50
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 208ms | 93ms | -115ms | -55.29
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 186ms | 87ms | -99ms | -53.15
| UserStore.GetProfilesInChannel | p99 | 435ms | 204ms | -231ms | -53.10
| PostStore.SetPostReminder | p99 | 459ms | 232ms | -227ms | -49.48
| ChannelBookmarkStore.Delete | p99 | 97ms | 49ms | -48ms | -49.23
| ChannelStore.AnalyticsCountAll | p99 | 98ms | 50ms | -48ms | -48.73
| StatusStore.UpdateExpiredDNDStatuses | p99 | 185ms | 96ms | -89ms | -47.98
| SessionStore.Remove | p99 | 181ms | 96ms | -85ms | -46.96
| LinkMetadataStore.Save | p99 | 96ms | 51ms | -45ms | -46.66
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 88ms | 48ms | -40ms | -45.20
| PostPersistentNotificationStore.DeleteExpired | p99 | 77ms | 44ms | -33ms | -42.86
| PropertyValueStore.SearchPropertyValues | p99 | 185ms | 107ms | -78ms | -42.15
| ChannelStore.GetSidebarCategory | p99 | 380ms | 225ms | -155ms | -40.79
| JobStore.Save | p99 | 134ms | 80ms | -54ms | -40.15
| ChannelStore.CreateInitialSidebarCategories | p99 | 451ms | 274ms | -177ms | -39.24
| UserStore.GetMany | p99 | 140ms | 89ms | -51ms | -36.30
| ChannelStore.CreateDirectChannel | p99 | 768ms | 491ms | -277ms | -36.07
| PostStore.GetPostsAfter | p99 | 147ms | 95ms | -52ms | -35.33
| JobStore.UpdateStatusOptimistically | p99 | 91ms | 61ms | -30ms | -33.15
| JobStore.UpdateOptimistically | p99 | 90ms | 62ms | -28ms | -30.94
| StatusStore.Get | p99 | 143ms | 101ms | -42ms | -29.33
| ClusterDiscoveryStore.SetLastPingAt | p99 | 196ms | 139ms | -57ms | -29.03
| ChannelStore.GetGuestCount | p99 | 139ms | 99ms | -40ms | -28.69
| UserStore.Get | p99 | 138ms | 99ms | -39ms | -28.19
| FileInfoStore.GetByIds | p99 | 165ms | 120ms | -45ms | -27.28
| PostStore.GetPostsByThread | p99 | 136ms | 100ms | -36ms | -26.49
| ChannelStore.GetFileCount | p99 | 135ms | 100ms | -35ms | -25.93
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 242ms | 183ms | -59ms | -24.38
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 131ms | 99ms | -32ms | -24.35
| FileInfoStore.GetForPost | p99 | 127ms | 97ms | -30ms | -23.61
| PreferenceStore.Get | p99 | 154ms | 119ms | -35ms | -22.69
| ThreadStore.GetMembershipForUser | p99 | 126ms | 98ms | -28ms | -22.23
| ReactionStore.GetForPost | p99 | 109ms | 85ms | -24ms | -22.03
| UserStore.GetProfileByIds | p99 | 180ms | 143ms | -37ms | -20.56
| PostStore.Save | p99 | 354ms | 282ms | -72ms | -20.35
| RoleStore.ChannelHigherScopedPermissions | p99 | 95ms | 76ms | -19ms | -20.05
| ProductNoticesStore.View | p99 | 614ms | 492ms | -122ms | -19.88
| ThreadStore.GetTeamsUnreadForUser | p99 | 171ms | 137ms | -34ms | -19.84
| UserStore.GetAllProfilesInChannel | p99 | 1.903s | 1.531s | -372ms | -19.55
| ThreadStore.GetThreadUnreadReplyCount | p99 | 179ms | 144ms | -35ms | -19.53
| ChannelStore.GetPublicChannelsForTeam | p99 | 221ms | 178ms | -43ms | -19.46
| ThreadStore.MarkAllAsReadByChannels | p99 | 113ms | 92ms | -21ms | -18.66
| ThreadStore.GetThreadFollowers | p99 | 99ms | 81ms | -18ms | -18.26
| PostAcknowledgementStore.GetForPosts | p99 | 200ms | 164ms | -36ms | -18.00
| ChannelStore.IsReadOnlyChannel | p99 | 158ms | 130ms | -28ms | -17.67
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 74ms | 61ms | -13ms | -17.60
| PreferenceStore.GetAll | p99 | 120ms | 99ms | -21ms | -17.50
| ChannelStore.GetMembersForUser | p99 | 169ms | 140ms | -29ms | -17.12
| ChannelStore.GetAllChannelMembersForUser | p99 | 150ms | 125ms | -25ms | -16.71
| ChannelStore.GetPinnedPostCount | p99 | 145ms | 121ms | -24ms | -16.59
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 229ms | 193ms | -36ms | -15.70
| PostPriorityStore.GetForPosts | p99 | 204ms | 172ms | -32ms | -15.65
| PostPersistentNotificationStore.GetSingle | p99 | 90ms | 76ms | -14ms | -15.57
| LinkMetadataStore.Get | p99 | 109ms | 92ms | -17ms | -15.55
| DraftStore.Upsert | p99 | 173ms | 147ms | -26ms | -15.02
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 113ms | 96ms | -17ms | -14.99
| FileInfoStore.Get | p99 | 175ms | 150ms | -25ms | -14.26
| PostStore.GetEtag | p99 | 175ms | 150ms | -25ms | -14.26
| ChannelStore.Get | p99 | 215ms | 185ms | -30ms | -13.96
| PostStore.GetPostsBefore | p99 | 182ms | 157ms | -25ms | -13.74
| ChannelStore.GetChannels | p99 | 184ms | 159ms | -25ms | -13.60
| ChannelStore.SearchGroupChannels | p99 | 191ms | 165ms | -26ms | -13.59
| UserStore.UpdateUpdateAt | p99 | 74ms | 64ms | -10ms | -13.54
| ChannelStore.GetByName | p99 | 112ms | 97ms | -15ms | -13.44
| TeamStore.GetMember | p99 | 84ms | 73ms | -11ms | -13.15
| UserStore.GetProfilesByUsernames | p99 | 185ms | 161ms | -24ms | -12.98
| TeamStore.Get | p99 | 96ms | 84ms | -12ms | -12.54
| ThreadStore.GetThreadsForUser | p99 | 192ms | 168ms | -24ms | -12.49
| TeamStore.GetTotalMemberCount | p99 | 241ms | 211ms | -30ms | -12.43
| WebhookStore.GetOutgoingByTeam | p99 | 184ms | 162ms | -22ms | -11.97
| UserStore.GetAllProfiles | p99 | 84ms | 74ms | -10ms | -11.96
| SessionStore.GetLRUSessions | p99 | 86ms | 76ms | -10ms | -11.67
| UserStore.Save | p99 | 383ms | 339ms | -44ms | -11.50
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 96ms | 85ms | -11ms | -11.49
| ChannelStore.SaveMember | p99 | 465ms | 413ms | -52ms | -11.19
| PostStore.GetSingle | p99 | 99ms | 88ms | -11ms | -11.17
| ThreadStore.GetThreadForUser | p99 | 209ms | 186ms | -23ms | -11.01
| JobStore.GetAllByStatus | p99 | 213ms | 190ms | -23ms | -10.82
| EmojiStore.GetByName | p99 | 104ms | 93ms | -11ms | -10.59
| UserStore.GetUnreadCount | p99 | 105ms | 94ms | -11ms | -10.48
| DraftStore.GetDraftsForUser | p99 | 187ms | 168ms | -19ms | -10.18
| SharedChannelStore.HasChannel | p99 | 108ms | 97ms | -11ms | -10.14
| JobStore.GetCountByStatusAndType | p99 | 211ms | 190ms | -21ms | -9.98
| ChannelStore.AutocompleteInTeamForSearch | p99 | 262ms | 236ms | -26ms | -9.93
| UserStore.UpdateLastLogin | p99 | 72ms | 65ms | -7ms | -9.74
| ChannelStore.GetMemberForPost | p99 | 196ms | 177ms | -19ms | -9.70
| DraftStore.Get | p99 | 195ms | 177ms | -18ms | -9.22
| ThreadStore.MaintainMembership | p99 | 227ms | 207ms | -20ms | -8.81
| GroupStore.GetGroups | p99 | 102ms | 93ms | -9ms | -8.79
| UserStore.AutocompleteUsersInChannel | p99 | 387ms | 354ms | -33ms | -8.52
| ChannelStore.GetChannelUnread | p99 | 192ms | 176ms | -16ms | -8.31
| PostStore.GetPostIdAfterTime | p99 | 75ms | 69ms | -6ms | -7.99
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 102ms | 94ms | -8ms | -7.81
| SessionStore.UpdateLastActivityAt | p99 | 90ms | 83ms | -7ms | -7.78
| StatusStore.UpdateLastActivityAt | p99 | 91ms | 84ms | -7ms | -7.67
| ChannelStore.GetMemberLastViewedAt | p99 | 94ms | 87ms | -7ms | -7.43
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 95ms | 88ms | -7ms | -7.37
| SessionStore.Save | p99 | 150ms | 139ms | -11ms | -7.33
| ThreadStore.GetTotalUnreadThreads | p99 | 98ms | 91ms | -7ms | -7.14
| ThreadStore.GetTotalUnreadMentions | p99 | 99ms | 92ms | -7ms | -7.07
| SystemStore.GetByName | p99 | 92ms | 86ms | -6ms | -6.50
| UserStore.UpdateFailedPasswordAttempts | p99 | 94ms | 88ms | -6ms | -6.40
| UserStore.IsEmpty | p99 | 48ms | 45ms | -3ms | -6.30
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 96ms | 90ms | -6ms | -6.26
| UserStore.GetForLogin | p99 | 97ms | 91ms | -6ms | -6.17
| ChannelStore.GetChannelsByUser | p99 | 98ms | 92ms | -6ms | -6.13
| PostAcknowledgementStore.GetForPost | p99 | 82ms | 77ms | -5ms | -6.12
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 99ms | 93ms | -6ms | -6.04
| TeamStore.GetAllPage | p99 | 100ms | 94ms | -6ms | -6.02
| PostStore.GetPosts | p99 | 85ms | 80ms | -5ms | -5.86
| FileInfoStore.SetContent | p99 | 214ms | 202ms | -12ms | -5.61
| UserTermsOfServiceStore.GetByUser | p99 | 96ms | 91ms | -5ms | -5.21
| ThreadStore.GetTotalThreads | p99 | 98ms | 93ms | -5ms | -5.08
| TeamStore.GetTeamsByUserId | p99 | 98ms | 93ms | -5ms | -5.08
| PostStore.GetPostIdBeforeTime | p99 | 99ms | 94ms | -5ms | -5.06
| ChannelStore.GetMembersForUserWithPagination | p99 | 99ms | 94ms | -5ms | -5.05
| StatusStore.GetByIds | p99 | 204ms | 194ms | -10ms | -4.90
| SessionStore.Get | p99 | 215ms | 205ms | -10ms | -4.65
| PostStore.GetPostsSince | p99 | 221ms | 211ms | -10ms | -4.53
| AuditStore.Save | p99 | 93ms | 89ms | -4ms | -4.31
| GroupStore.GetByName | p99 | 93ms | 89ms | -4ms | -4.30
| FileInfoStore.AttachToPost | p99 | 193ms | 185ms | -8ms | -4.16
| TeamStore.GetActiveMemberCount | p99 | 241ms | 231ms | -10ms | -4.14
| TeamStore.GetTeamsForUser | p99 | 97ms | 93ms | -4ms | -4.13
| PostStore.Get | p99 | 243ms | 233ms | -10ms | -4.11
| ChannelStore.GetMember | p99 | 98ms | 94ms | -4ms | -4.08
| ChannelStore.GetMemberCount | p99 | 229ms | 220ms | -9ms | -3.94
| PostStore.Delete | p99 | 241ms | 232ms | -9ms | -3.73
| ThreadStore.MarkAsRead | p99 | 88ms | 85ms | -3ms | -3.41
| ThreadStore.UpdateMembership | p99 | 89ms | 86ms | -3ms | -3.36
| ChannelStore.UpdateLastViewedAt | p99 | 93ms | 90ms | -3ms | -3.21
| ChannelStore.IncrementMentionCount | p99 | 98ms | 95ms | -3ms | -3.06
| UserStore.Count | p99 | 174ms | 169ms | -5ms | -2.87
| TeamStore.SaveMember | p99 | 248ms | 241ms | -7ms | -2.83
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 78ms | 76ms | -2ms | -2.56
| PreferenceStore.Save | p99 | 244ms | 238ms | -6ms | -2.46
| PropertyFieldStore.SearchPropertyFields | p99 | 96ms | 94ms | -2ms | -2.09
| ThreadStore.Get | p99 | 98ms | 96ms | -2ms | -2.04
| DraftStore.Delete | p99 | 100ms | 98ms | -2ms | -2.00
| UserStore.Search | p99 | 237ms | 234ms | -3ms | -1.26
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 4ms | 19ms | 15ms | 348.31
| getPrevTrialLicense | avg | 2ms | 8ms | 6ms | 324.47
| getFilteredUsersStats | avg | 14ms | 54ms | 40ms | 293.33
| getUsersByGroupChannelIds | avg | 65ms | 149ms | 84ms | 129.94
| deleteChannelBookmark | avg | 37ms | 57ms | 20ms | 53.86
| handleCheckCWSConnection | avg | 72ms | 104ms | 32ms | 44.61
| getGroups | avg | 12ms | 15ms | 3ms | 24.30
| followThreadByUser | avg | 56ms | 65ms | 9ms | 16.11
| setPostReminder | avg | 86ms | 98ms | 12ms | 14.02
| createChannelBookmark | avg | 24ms | 26ms | 2ms | 8.44
| removeUserCustomStatus | avg | 275ms | 296ms | 21ms | 7.62
| createGroupChannel | avg | 689ms | 721ms | 32ms | 4.65
| searchPostsInTeam | avg | 175ms | 178ms | 3ms | 1.71
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | p99 | 25ms | 246ms | 221ms | 889.11
| updateReadStateAllThreadsByUser | p99 | 5ms | 49ms | 44ms | 888.80
| getPrevTrialLicense | p99 | 5ms | 25ms | 20ms | 404.04
| getUsersByGroupChannelIds | p99 | 100ms | 495ms | 395ms | 396.98
| handleCheckCWSConnection | p99 | 100ms | 247ms | 147ms | 147.74
| createChannel | p99 | 2.155s | 4.35s | 2.195s | 101.86
| deleteChannelBookmark | p99 | 50ms | 99ms | 49ms | 98.46
| getRolesByNames | p99 | 5ms | 9ms | 4ms | 80.81
| followThreadByUser | p99 | 461ms | 810ms | 349ms | 75.66
| createChannelBookmark | p99 | 93ms | 97ms | 4ms | 4.32
| getChannel | p99 | 221ms | 229ms | 8ms | 3.62
| removeUserCustomStatus | p99 | 947ms | 976ms | 29ms | 3.06
| searchPostsInTeam | p99 | 2.289s | 2.35s | 61ms | 2.66
| searchAllChannels | p99 | 238ms | 241ms | 3ms | 1.26
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFilesInTeam | avg | 9ms | 0s | -9ms | -105.01
| createEmoji | avg | 8ms | 0s | -8ms | -104.01
| autocompleteEmojis | avg | 34ms | 0s | -34ms | -99.08
| channelMemberCountsByGroup | avg | 18ms | 0s | -18ms | -98.94
| updateChannelBookmark | avg | 94ms | 18ms | -76ms | -80.64
| updateChannelBookmarkSortOrder | avg | 59ms | 20ms | -39ms | -66.23
| getUserByUsername | avg | 41ms | 15ms | -26ms | -63.36
| getChannelMembers | avg | 20ms | 8ms | -12ms | -59.93
| getServerLimits | avg | 38ms | 17ms | -21ms | -54.79
| getCategoriesForTeamForUser | avg | 32ms | 15ms | -17ms | -52.77
| autocompleteChannelsForTeamForSearch | avg | 76ms | 42ms | -34ms | -44.81
| getGroupsAssociatedToChannelsByTeam | avg | 78ms | 49ms | -29ms | -37.10
| updateCategoriesForTeamForUser | avg | 208ms | 134ms | -74ms | -35.53
| listCPAValues | avg | 15ms | 11ms | -4ms | -26.82
| unfollowThreadByUser | avg | 58ms | 43ms | -15ms | -25.96
| deletePost | avg | 79ms | 60ms | -19ms | -24.19
| getAnalytics | avg | 176ms | 134ms | -42ms | -23.88
| logout | avg | 162ms | 126ms | -36ms | -22.22
| getTeamStats | avg | 88ms | 72ms | -16ms | -18.17
| getPostsForChannel | avg | 109ms | 91ms | -18ms | -16.56
| getUsers | avg | 14ms | 12ms | -2ms | -14.51
| addChannelMember | avg | 474ms | 409ms | -65ms | -13.71
| getUser | avg | 15ms | 13ms | -2ms | -13.20
| deleteDraft | avg | 16ms | 14ms | -2ms | -12.58
| searchGroupChannels | avg | 16ms | 14ms | -2ms | -12.33
| updatePreferences | avg | 36ms | 32ms | -4ms | -11.13
| getChannelMember | avg | 19ms | 17ms | -2ms | -10.43
| getClientConfig | avg | 20ms | 18ms | -2ms | -10.12
| getProfileImage | avg | 91ms | 82ms | -9ms | -9.89
| updateReadStateThreadByUser | avg | 134ms | 121ms | -13ms | -9.70
| getPostThread | avg | 62ms | 56ms | -6ms | -9.68
| viewChannel | avg | 52ms | 47ms | -5ms | -9.64
| getPublicChannelsForTeam | avg | 33ms | 30ms | -3ms | -9.13
| getPostsForChannelAroundLastUnread | avg | 46ms | 42ms | -4ms | -8.73
| createPost | avg | 658ms | 603ms | -55ms | -8.35
| saveReaction | avg | 38ms | 35ms | -3ms | -7.98
| addTeamMember | avg | 1.295s | 1.209s | -86ms | -6.64
| createChannel | avg | 513ms | 483ms | -30ms | -5.85
| createDirectChannel | avg | 479ms | 455ms | -24ms | -5.01
| getFileThumbnail | avg | 60ms | 57ms | -3ms | -4.98
| createUser | avg | 292ms | 278ms | -14ms | -4.80
| getFilePreview | avg | 70ms | 67ms | -3ms | -4.29
| login | avg | 118ms | 113ms | -5ms | -4.24
| uploadFileStream | avg | 608ms | 584ms | -24ms | -3.95
| searchUsers | avg | 52ms | 50ms | -2ms | -3.88
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| searchFilesInTeam | p99 | 10ms | 0s | -10ms | -100.46
| autocompleteEmojis | p99 | 99ms | 0s | -99ms | -99.95
| channelMemberCountsByGroup | p99 | 212ms | 0s | -212ms | -99.77
| updateChannelBookmark | p99 | 950ms | 50ms | -900ms | -94.74
| getUserByUsername | p99 | 245ms | 49ms | -196ms | -79.84
| getServerLimits | p99 | 99ms | 25ms | -74ms | -74.75
| updateChannelBookmarkSortOrder | p99 | 99ms | 25ms | -74ms | -74.55
| getGroupsAssociatedToChannelsByTeam | p99 | 247ms | 99ms | -148ms | -59.92
| updateCategoriesForTeamForUser | p99 | 1.945s | 835ms | -1.11s | -57.07
| getAnalytics | p99 | 495ms | 247ms | -248ms | -50.10
| getChannelMembers | p99 | 49ms | 25ms | -24ms | -48.61
| deletePost | p99 | 471ms | 244ms | -227ms | -48.17
| listCPAValues | p99 | 197ms | 113ms | -84ms | -42.66
| getPostsForChannel | p99 | 1.257s | 896ms | -361ms | -28.73
| addTeamMember | p99 | 8.007s | 5.894s | -2.113s | -26.39
| getProfileImage | p99 | 652ms | 496ms | -156ms | -23.91
| saveReaction | p99 | 338ms | 264ms | -74ms | -21.87
| getCategoriesForTeamForUser | p99 | 246ms | 194ms | -52ms | -21.14
| getPreferences | p99 | 132ms | 108ms | -24ms | -18.25
| unfollowThreadByUser | p99 | 450ms | 368ms | -82ms | -18.21
| listChannelBookmarksForChannel | p99 | 165ms | 136ms | -29ms | -17.60
| getAllTeams | p99 | 153ms | 126ms | -27ms | -17.59
| patchPost | p99 | 777ms | 642ms | -135ms | -17.36
| getUserStatusesByIds | p99 | 88ms | 73ms | -15ms | -17.10
| getChannelStats | p99 | 169ms | 141ms | -28ms | -16.60
| logout | p99 | 885ms | 740ms | -145ms | -16.38
| getChannelMembersForTeamForUser | p99 | 175ms | 147ms | -28ms | -15.97
| createPost | p99 | 4.24s | 3.566s | -674ms | -15.90
| searchGroupChannels | p99 | 195ms | 166ms | -29ms | -14.89
| getTeamMembersForUser | p99 | 128ms | 109ms | -19ms | -14.84
| createUser | p99 | 1.983s | 1.706s | -277ms | -13.97
| addChannelMember | p99 | 2.362s | 2.037s | -325ms | -13.76
| updateReadStateThreadByUser | p99 | 899ms | 777ms | -122ms | -13.57
| getFileThumbnail | p99 | 406ms | 354ms | -52ms | -12.82
| getPublicChannelsForTeam | p99 | 224ms | 197ms | -27ms | -12.07
| getChannelsForTeamForUser | p99 | 189ms | 167ms | -22ms | -11.65
| getUsersByNames | p99 | 192ms | 171ms | -21ms | -10.92
| getChannelMembersForUser | p99 | 106ms | 95ms | -11ms | -10.42
| getDrafts | p99 | 200ms | 180ms | -20ms | -10.01
| login | p99 | 883ms | 795ms | -88ms | -9.96
| getTeamScheduledPosts | p99 | 216ms | 195ms | -21ms | -9.74
| getThreadsForUser | p99 | 201ms | 182ms | -19ms | -9.44
| autocompleteUsers | p99 | 381ms | 346ms | -35ms | -9.19
| getPostsForChannelAroundLastUnread | p99 | 454ms | 413ms | -41ms | -9.02
| autocompleteChannelsForTeamForSearch | p99 | 262ms | 239ms | -23ms | -8.78
| getChannelUnread | p99 | 218ms | 200ms | -18ms | -8.26
| getUsersByIds | p99 | 49ms | 45ms | -4ms | -8.10
| getUsers | p99 | 224ms | 206ms | -18ms | -8.04
| getUser | p99 | 231ms | 213ms | -18ms | -7.80
| listCPAFields | p99 | 130ms | 120ms | -10ms | -7.69
| getFilePreview | p99 | 440ms | 407ms | -33ms | -7.51
| deleteDraft | p99 | 205ms | 190ms | -15ms | -7.31
| getTeamsUnreadForUser | p99 | 223ms | 207ms | -16ms | -7.19
| viewChannel | p99 | 483ms | 451ms | -32ms | -6.63
| upsertDraft | p99 | 214ms | 200ms | -14ms | -6.55
| getChannelMember | p99 | 232ms | 217ms | -15ms | -6.46
| updatePreferences | p99 | 377ms | 354ms | -23ms | -6.10
| getChannelsForUser | p99 | 100ms | 94ms | -6ms | -6.01
| createDirectChannel | p99 | 2.443s | 2.297s | -146ms | -5.98
| getPostThread | p99 | 487ms | 458ms | -29ms | -5.96
| getTeamsForUser | p99 | 100ms | 95ms | -5ms | -5.02
| getClientConfig | p99 | 237ms | 229ms | -8ms | -3.38
| getTeamMember | p99 | 147ms | 143ms | -4ms | -2.73
| setPostReminder | p99 | 835ms | 815ms | -20ms | -2.40
| uploadFileStream | p99 | 2.363s | 2.314s | -49ms | -2.07
| searchUsers | p99 | 240ms | 236ms | -4ms | -1.67
| createGroupChannel | p99 | 3.925s | 3.86s | -65ms | -1.66
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 9ms| 8ms | -1ms | -11.525
| |  P99| 93ms| 89ms | -4ms | -4.307
| BotStore.Get |  Avg| 10ms| 14ms | 4ms | 40.592
| |  P99| 93ms| 428ms | 335ms | 360.215
| ChannelBookmarkStore.Delete |  Avg| 19ms| 17ms | -2ms | -10.721
| |  P99| 97ms| 49ms | -48ms | -49.231
| ChannelBookmarkStore.Get |  Avg| 17ms| 4ms | -13ms | -75.612
| |  P99| 231ms| 24ms | -207ms | -89.513
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 10ms| 9ms | -1ms | -10.326
| |  P99| 131ms| 99ms | -32ms | -24.353
| ChannelBookmarkStore.Save |  Avg| 15ms| 20ms | 5ms | 33.198
| |  P99| 96ms| 228ms | 132ms | 137.739
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 15ms| 7ms | -8ms | -52.385
| |  P99| 49ms| 10ms | -39ms | -79.571
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 6ms | -1ms | -15.112
| |  P99| 74ms| 61ms | -13ms | -17.597
| ChannelStore.AnalyticsCountAll |  Avg| 37ms| 26ms | -11ms | -29.590
| |  P99| 98ms| 50ms | -48ms | -48.731
| ChannelStore.Autocomplete |  Avg| 51ms| 51ms | 0s | 0.000
| |  P99| 236ms| 240ms | 4ms | 1.693
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 76ms| 41ms | -35ms | -46.312
| |  P99| 262ms| 236ms | -26ms | -9.929
| ChannelStore.CreateDirectChannel |  Avg| 77ms| 66ms | -11ms | -14.349
| |  P99| 768ms| 491ms | -277ms | -36.075
| ChannelStore.CreateInitialSidebarCategories |  Avg| 43ms| 29ms | -14ms | -32.606
| |  P99| 451ms| 274ms | -177ms | -39.237
| ChannelStore.Get |  Avg| 18ms| 16ms | -2ms | -10.841
| |  P99| 215ms| 185ms | -30ms | -13.960
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 12ms | -1ms | -7.796
| |  P99| 150ms| 125ms | -25ms | -16.712
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 23ms| 19ms | -4ms | -17.122
| |  P99| 229ms| 193ms | -36ms | -15.701
| ChannelStore.GetByName |  Avg| 12ms| 11ms | -1ms | -8.558
| |  P99| 112ms| 97ms | -15ms | -13.439
| ChannelStore.GetByNameIncludeDeleted |  Avg| 5ms| 0s | -5ms | -102.574
| |  P99| 25ms| 0s | -25ms | -101.833
| ChannelStore.GetChannelUnread |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 192ms| 176ms | -16ms | -8.314
| ChannelStore.GetChannels |  Avg| 14ms| 12ms | -2ms | -14.713
| |  P99| 184ms| 159ms | -25ms | -13.599
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 8ms | -1ms | -11.311
| |  P99| 98ms| 92ms | -6ms | -6.131
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 9ms | -1ms | -10.429
| |  P99| 113ms| 96ms | -17ms | -14.993
| ChannelStore.GetFileCount |  Avg| 12ms| 11ms | -1ms | -8.345
| |  P99| 135ms| 100ms | -35ms | -25.926
| ChannelStore.GetGuestCount |  Avg| 11ms| 10ms | -1ms | -8.789
| |  P99| 139ms| 99ms | -40ms | -28.692
| ChannelStore.GetMember |  Avg| 9ms| 8ms | -1ms | -11.497
| |  P99| 98ms| 94ms | -4ms | -4.078
| ChannelStore.GetMemberCount |  Avg| 39ms| 36ms | -3ms | -7.606
| |  P99| 229ms| 220ms | -9ms | -3.938
| ChannelStore.GetMemberCountsByGroup |  Avg| 18ms| 0s | -18ms | -102.390
| |  P99| 212ms| 0s | -212ms | -99.766
| ChannelStore.GetMemberForPost |  Avg| 17ms| 16ms | -1ms | -5.852
| |  P99| 196ms| 177ms | -19ms | -9.704
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 94ms| 87ms | -7ms | -7.435
| ChannelStore.GetMembers |  Avg| 19ms| 6ms | -13ms | -69.026
| |  P99| 49ms| 10ms | -39ms | -78.987
| ChannelStore.GetMembersForUser |  Avg| 13ms| 12ms | -1ms | -7.593
| |  P99| 169ms| 140ms | -29ms | -17.118
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 14ms| 11ms | -3ms | -20.920
| |  P99| 186ms| 87ms | -99ms | -53.153
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 9ms | -1ms | -10.119
| |  P99| 99ms| 94ms | -5ms | -5.054
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 9ms | -1ms | -9.964
| |  P99| 145ms| 121ms | -24ms | -16.594
| ChannelStore.GetPublicChannelsForTeam |  Avg| 32ms| 28ms | -4ms | -12.643
| |  P99| 221ms| 178ms | -43ms | -19.462
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 31ms| 14ms | -17ms | -54.906
| |  P99| 242ms| 183ms | -59ms | -24.380
| ChannelStore.GetSidebarCategory |  Avg| 32ms| 25ms | -7ms | -22.123
| |  P99| 380ms| 225ms | -155ms | -40.792
| ChannelStore.GetTeamChannels |  Avg| 42ms| 48ms | 6ms | 14.425
| |  P99| 238ms| 435ms | 197ms | 82.600
| ChannelStore.IncrementMentionCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 98ms| 95ms | -3ms | -3.057
| ChannelStore.IsReadOnlyChannel |  Avg| 11ms| 10ms | -1ms | -8.846
| |  P99| 158ms| 130ms | -28ms | -17.668
| ChannelStore.Save |  Avg| 37ms| 48ms | 11ms | 29.629
| |  P99| 325ms| 477ms | 152ms | 46.773
| ChannelStore.SaveMember |  Avg| 58ms| 53ms | -5ms | -8.616
| |  P99| 465ms| 413ms | -52ms | -11.192
| ChannelStore.SearchGroupChannels |  Avg| 16ms| 14ms | -2ms | -12.625
| |  P99| 191ms| 165ms | -26ms | -13.585
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 9ms | -1ms | -10.283
| |  P99| 93ms| 90ms | -3ms | -3.213
| ChannelStore.UpdateSidebarCategories |  Avg| 133ms| 75ms | -58ms | -43.663
| |  P99| 1.39s| 467ms | -923ms | -66.406
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 6ms | -1ms | -13.918
| |  P99| 95ms| 88ms | -7ms | -7.375
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 16ms| 14ms | -2ms | -12.814
| |  P99| 196ms| 139ms | -57ms | -29.026
| CommandWebhookStore.Cleanup |  Avg| 14ms| 52ms | 38ms | 270.176
| |  P99| 98ms| 244ms | 146ms | 148.980
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 0s | -2ms | -94.324
| |  P99| 5ms| 0s | -5ms | -100.959
| DraftStore.Delete |  Avg| 12ms| 11ms | -1ms | -8.668
| |  P99| 100ms| 98ms | -2ms | -2.003
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 15ms | 3ms | 24.684
| |  P99| 88ms| 48ms | -40ms | -45.199
| DraftStore.Get |  Avg| 15ms| 13ms | -2ms | -13.382
| |  P99| 195ms| 177ms | -18ms | -9.216
| DraftStore.GetDraftsForUser |  Avg| 15ms| 13ms | -2ms | -13.738
| |  P99| 187ms| 168ms | -19ms | -10.180
| DraftStore.Upsert |  Avg| 14ms| 13ms | -1ms | -7.339
| |  P99| 173ms| 147ms | -26ms | -15.018
| EmojiStore.GetByName |  Avg| 9ms| 8ms | -1ms | -10.922
| |  P99| 104ms| 93ms | -11ms | -10.585
| EmojiStore.GetMultipleByName |  Avg| 3ms| 6ms | 3ms | 111.214
| |  P99| 24ms| 24ms | 0s | 0.000
| EmojiStore.Search |  Avg| 34ms| 0s | -34ms | -99.279
| |  P99| 99ms| 0s | -99ms | -99.951
| FileInfoStore.AttachToPost |  Avg| 17ms| 15ms | -2ms | -12.117
| |  P99| 193ms| 185ms | -8ms | -4.156
| FileInfoStore.Get |  Avg| 12ms| 11ms | -1ms | -8.330
| |  P99| 175ms| 150ms | -25ms | -14.264
| FileInfoStore.GetByIds |  Avg| 10ms| 9ms | -1ms | -10.167
| |  P99| 165ms| 120ms | -45ms | -27.285
| FileInfoStore.GetForPost |  Avg| 10ms| 8ms | -2ms | -20.830
| |  P99| 127ms| 97ms | -30ms | -23.609
| FileInfoStore.Save |  Avg| 14ms| 13ms | -1ms | -7.121
| |  P99| 150ms| 170ms | 20ms | 13.292
| FileInfoStore.Search |  Avg| 3ms| 0s | -3ms | -118.451
| |  P99| 5ms| 0s | -5ms | -100.931
| FileInfoStore.SetContent |  Avg| 19ms| 18ms | -1ms | -5.180
| |  P99| 214ms| 202ms | -12ms | -5.607
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 76ms | -2ms | -2.556
| GroupStore.GetByName |  Avg| 8ms| 7ms | -1ms | -12.796
| |  P99| 93ms| 89ms | -4ms | -4.297
| GroupStore.GetGroups |  Avg| 10ms| 9ms | -1ms | -10.294
| |  P99| 102ms| 93ms | -9ms | -8.791
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 53ms| 12ms | -41ms | -77.688
| |  P99| 245ms| 25ms | -220ms | -89.613
| JobStore.GetAllByStatus |  Avg| 15ms| 13ms | -2ms | -13.137
| |  P99| 213ms| 190ms | -23ms | -10.819
| JobStore.GetCountByStatusAndType |  Avg| 14ms| 12ms | -2ms | -14.144
| |  P99| 211ms| 190ms | -21ms | -9.976
| JobStore.GetNewestJobByStatusesAndType |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 170ms | 77ms | 83.019
| JobStore.Save |  Avg| 13ms| 9ms | -4ms | -30.683
| |  P99| 134ms| 80ms | -54ms | -40.149
| JobStore.UpdateOptimistically |  Avg| 9ms| 7ms | -2ms | -22.550
| |  P99| 90ms| 62ms | -28ms | -30.940
| JobStore.UpdateStatus |  Avg| 14ms| 9ms | -5ms | -37.010
| |  P99| 221ms| 90ms | -131ms | -59.144
| JobStore.UpdateStatusOptimistically |  Avg| 11ms| 7ms | -4ms | -37.725
| |  P99| 91ms| 61ms | -30ms | -33.149
| LicenseStore.GetAll |  Avg| 1ms| 5ms | 4ms | 303.664
| |  P99| 5ms| 25ms | 20ms | 404.040
| LinkMetadataStore.Get |  Avg| 9ms| 7ms | -2ms | -22.613
| |  P99| 109ms| 92ms | -17ms | -15.546
| LinkMetadataStore.Save |  Avg| 9ms| 7ms | -2ms | -22.331
| |  P99| 96ms| 51ms | -45ms | -46.660
| PluginStore.Delete |  Avg| 5ms| 0s | -5ms | -99.398
| |  P99| 66ms| 0s | -66ms | -99.508
| PluginStore.Get |  Avg| 3ms| 0s | -3ms | -94.613
| |  P99| 22ms| 0s | -22ms | -98.655
| PluginStore.List |  Avg| 7ms| 13ms | 6ms | 86.818
| |  P99| 72ms| 95ms | 23ms | 31.944
| PluginStore.SetWithOptions |  Avg| 11ms| 0s | -11ms | -97.228
| |  P99| 140ms| 0s | -140ms | -99.845
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 6ms | -1ms | -14.726
| |  P99| 82ms| 77ms | -5ms | -6.116
| PostAcknowledgementStore.GetForPosts |  Avg| 13ms| 11ms | -2ms | -15.441
| |  P99| 200ms| 164ms | -36ms | -18.005
| PostPersistentNotificationStore.DeleteExpired |  Avg| 7ms| 3ms | -4ms | -56.108
| |  P99| 77ms| 44ms | -33ms | -42.859
| PostPersistentNotificationStore.Get |  Avg| 9ms| 3ms | -6ms | -64.808
| |  P99| 88ms| 38ms | -50ms | -56.498
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 6ms | -1ms | -14.010
| |  P99| 90ms| 76ms | -14ms | -15.571
| PostPriorityStore.GetForPost |  Avg| 6ms| 8ms | 2ms | 34.119
| |  P99| 71ms| 88ms | 17ms | 23.831
| PostPriorityStore.GetForPosts |  Avg| 14ms| 12ms | -2ms | -14.630
| |  P99| 204ms| 172ms | -32ms | -15.653
| PostStore.AnalyticsPostCount |  Avg| 289ms| 392ms | 103ms | 35.699
| |  P99| 498ms| 990ms | 492ms | 98.894
| PostStore.AnalyticsPostCountByTeam |  Avg| 5ms| 2ms | -3ms | -58.557
| |  P99| 25ms| 5ms | -20ms | -81.466
| PostStore.Delete |  Avg| 42ms| 33ms | -9ms | -21.297
| |  P99| 241ms| 232ms | -9ms | -3.729
| PostStore.Get |  Avg| 27ms| 25ms | -2ms | -7.332
| |  P99| 243ms| 233ms | -10ms | -4.111
| PostStore.GetEtag |  Avg| 13ms| 11ms | -2ms | -15.900
| |  P99| 175ms| 150ms | -25ms | -14.261
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 5ms | -1ms | -18.179
| |  P99| 75ms| 69ms | -6ms | -7.986
| PostStore.GetPostIdBeforeTime |  Avg| 9ms| 8ms | -1ms | -11.571
| |  P99| 99ms| 94ms | -5ms | -5.063
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 11ms | 1ms | 9.575
| |  P99| 92ms| 140ms | 48ms | 52.387
| PostStore.GetPostReminders |  Avg| 25ms| 22ms | -3ms | -11.783
| |  P99| 229ms| 228ms | -1ms | -0.437
| PostStore.GetPosts |  Avg| 8ms| 7ms | -1ms | -12.277
| |  P99| 85ms| 80ms | -5ms | -5.861
| PostStore.GetPostsAfter |  Avg| 12ms| 10ms | -2ms | -16.697
| |  P99| 147ms| 95ms | -52ms | -35.333
| PostStore.GetPostsBefore |  Avg| 15ms| 13ms | -2ms | -13.770
| |  P99| 182ms| 157ms | -25ms | -13.736
| PostStore.GetPostsByThread |  Avg| 17ms| 16ms | -1ms | -5.905
| |  P99| 136ms| 100ms | -36ms | -26.493
| PostStore.GetPostsSince |  Avg| 27ms| 26ms | -1ms | -3.689
| |  P99| 221ms| 211ms | -10ms | -4.535
| PostStore.GetSingle |  Avg| 8ms| 7ms | -1ms | -11.789
| |  P99| 99ms| 88ms | -11ms | -11.166
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 33ms| 30ms | -3ms | -9.064
| |  P99| 354ms| 282ms | -72ms | -20.353
| PostStore.SearchPostsForUser |  Avg| 152ms| 158ms | 6ms | 3.954
| |  P99| 2.28s| 2.344s | 64ms | 2.808
| PostStore.SetPostReminder |  Avg| 40ms| 33ms | -7ms | -17.531
| |  P99| 459ms| 232ms | -227ms | -49.483
| PostStore.Update |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 233ms| 320ms | 87ms | 37.328
| PreferenceStore.DeleteCategoryAndName |  Avg| 6ms| 18ms | 12ms | 186.469
| |  P99| 44ms| 214ms | 170ms | 383.965
| PreferenceStore.Get |  Avg| 11ms| 10ms | -1ms | -9.084
| |  P99| 154ms| 119ms | -35ms | -22.695
| PreferenceStore.GetAll |  Avg| 10ms| 9ms | -1ms | -10.134
| |  P99| 120ms| 99ms | -21ms | -17.497
| PreferenceStore.Save |  Avg| 25ms| 23ms | -2ms | -8.018
| |  P99| 244ms| 238ms | -6ms | -2.460
| ProductNoticesStore.ClearOldNotices |  Avg| 25ms| 30ms | 5ms | 19.721
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 46ms| 8ms | -38ms | -83.383
| |  P99| 245ms| 25ms | -220ms | -89.613
| ProductNoticesStore.View |  Avg| 69ms| 63ms | -6ms | -8.717
| |  P99| 614ms| 492ms | -122ms | -19.877
| PropertyFieldStore.SearchPropertyFields |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 96ms| 94ms | -2ms | -2.094
| PropertyValueStore.SearchPropertyValues |  Avg| 14ms| 11ms | -3ms | -21.692
| |  P99| 185ms| 107ms | -78ms | -42.150
| ReactionStore.GetForPost |  Avg| 10ms| 9ms | -1ms | -9.649
| |  P99| 109ms| 85ms | -24ms | -22.033
| RoleStore.ChannelHigherScopedPermissions |  Avg| 15ms| 16ms | 1ms | 6.565
| |  P99| 95ms| 76ms | -19ms | -20.047
| RoleStore.GetByNames |  Avg| 6ms| 19ms | 13ms | 202.967
| |  P99| 82ms| 215ms | 133ms | 161.702
| ScheduledPostStore.CreateScheduledPost |  Avg| 17ms| 18ms | 1ms | 6.020
| |  P99| 207ms| 206ms | -1ms | -0.484
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 12ms| 16ms | 4ms | 33.848
| |  P99| 208ms| 93ms | -115ms | -55.288
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 8ms| 7ms | -1ms | -12.517
| |  P99| 96ms| 90ms | -6ms | -6.257
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 12ms| 18ms | 6ms | 51.922
| |  P99| 208ms| 207ms | -1ms | -0.481
| SessionStore.Get |  Avg| 17ms| 16ms | -1ms | -5.772
| |  P99| 215ms| 205ms | -10ms | -4.651
| SessionStore.GetLRUSessions |  Avg| 7ms| 6ms | -1ms | -14.656
| |  P99| 86ms| 76ms | -10ms | -11.668
| SessionStore.GetSessionsExpired |  Avg| 13ms| 4ms | -9ms | -69.979
| |  P99| 233ms| 23ms | -210ms | -89.937
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 7ms | -1ms | -12.851
| |  P99| 96ms| 85ms | -11ms | -11.490
| SessionStore.Remove |  Avg| 14ms| 12ms | -2ms | -14.270
| |  P99| 181ms| 96ms | -85ms | -46.963
| SessionStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 150ms| 139ms | -11ms | -7.330
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 8ms | -1ms | -11.112
| |  P99| 90ms| 83ms | -7ms | -7.781
| SharedChannelStore.HasChannel |  Avg| 9ms| 8ms | -1ms | -10.840
| |  P99| 108ms| 97ms | -11ms | -10.144
| StatusStore.Get |  Avg| 10ms| 9ms | -1ms | -10.049
| |  P99| 143ms| 101ms | -42ms | -29.332
| StatusStore.GetByIds |  Avg| 17ms| 15ms | -2ms | -11.935
| |  P99| 204ms| 194ms | -10ms | -4.896
| StatusStore.SaveOrUpdate |  Avg| 26ms| 11ms | -15ms | -57.311
| |  P99| 401ms| 115ms | -286ms | -71.389
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 13ms| 12ms | -1ms | -7.563
| |  P99| 185ms| 96ms | -89ms | -47.978
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 91ms| 84ms | -7ms | -7.674
| SystemStore.GetByName |  Avg| 7ms| 6ms | -1ms | -15.021
| |  P99| 92ms| 86ms | -6ms | -6.497
| TeamStore.AnalyticsTeamCount |  Avg| 7ms| 4ms | -3ms | -43.064
| |  P99| 25ms| 10ms | -15ms | -61.100
| TeamStore.Get |  Avg| 8ms| 6ms | -2ms | -25.452
| |  P99| 96ms| 84ms | -12ms | -12.543
| TeamStore.GetActiveMemberCount |  Avg| 79ms| 66ms | -13ms | -16.386
| |  P99| 241ms| 231ms | -10ms | -4.143
| TeamStore.GetAllPage |  Avg| 9ms| 8ms | -1ms | -11.663
| |  P99| 100ms| 94ms | -6ms | -6.022
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 8ms | -1ms | -11.066
| |  P99| 102ms| 94ms | -8ms | -7.807
| TeamStore.GetMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 84ms| 73ms | -11ms | -13.154
| TeamStore.GetTeamsByUserId |  Avg| 9ms| 8ms | -1ms | -11.585
| |  P99| 98ms| 93ms | -5ms | -5.080
| TeamStore.GetTeamsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 97ms| 93ms | -4ms | -4.129
| TeamStore.GetTotalMemberCount |  Avg| 70ms| 55ms | -15ms | -21.550
| |  P99| 241ms| 211ms | -30ms | -12.429
| TeamStore.SaveMember |  Avg| 42ms| 39ms | -3ms | -7.202
| |  P99| 248ms| 241ms | -7ms | -2.826
| ThreadStore.Get |  Avg| 9ms| 8ms | -1ms | -11.655
| |  P99| 98ms| 96ms | -2ms | -2.036
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 9ms | -1ms | -10.281
| |  P99| 126ms| 98ms | -28ms | -22.230
| ThreadStore.GetTeamsUnreadForUser |  Avg| 12ms| 11ms | -1ms | -8.224
| |  P99| 171ms| 137ms | -34ms | -19.838
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 7ms | -1ms | -12.209
| |  P99| 99ms| 81ms | -18ms | -18.257
| ThreadStore.GetThreadForUser |  Avg| 18ms| 16ms | -2ms | -10.954
| |  P99| 209ms| 186ms | -23ms | -11.012
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 20ms| 19ms | -1ms | -4.924
| |  P99| 179ms| 144ms | -35ms | -19.535
| ThreadStore.GetThreadsForUser |  Avg| 16ms| 14ms | -2ms | -12.792
| |  P99| 192ms| 168ms | -24ms | -12.487
| ThreadStore.GetTotalThreads |  Avg| 9ms| 8ms | -1ms | -11.410
| |  P99| 98ms| 93ms | -5ms | -5.083
| ThreadStore.GetTotalUnreadMentions |  Avg| 9ms| 8ms | -1ms | -11.316
| |  P99| 99ms| 92ms | -7ms | -7.070
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 8ms | -1ms | -11.399
| |  P99| 98ms| 91ms | -7ms | -7.144
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 8ms | -1ms | -10.926
| |  P99| 99ms| 93ms | -6ms | -6.038
| ThreadStore.MaintainMembership |  Avg| 18ms| 15ms | -3ms | -17.012
| |  P99| 227ms| 207ms | -20ms | -8.813
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 8ms | -1ms | -10.750
| |  P99| 113ms| 92ms | -21ms | -18.664
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 19ms | 15ms | 356.756
| |  P99| 5ms| 49ms | 44ms | 888.796
| ThreadStore.MarkAsRead |  Avg| 9ms| 8ms | -1ms | -11.547
| |  P99| 88ms| 85ms | -3ms | -3.413
| ThreadStore.UpdateMembership |  Avg| 9ms| 8ms | -1ms | -11.764
| |  P99| 89ms| 86ms | -3ms | -3.359
| TokenStore.Cleanup |  Avg| 2ms| 48ms | 46ms | 2405.264
| |  P99| 5ms| 244ms | 239ms | 4827.661
| UserAccessTokenStore.GetByToken |  Avg| 9ms| 11ms | 2ms | 23.279
| |  P99| 87ms| 157ms | 70ms | 80.001
| UserStore.AnalyticsActiveCount |  Avg| 31ms| 32ms | 1ms | 3.278
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 17ms| 10ms | -7ms | -42.252
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 74ms| 73ms | -1ms | -1.345
| |  P99| 387ms| 354ms | -33ms | -8.517
| UserStore.Count |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 174ms| 169ms | -5ms | -2.866
| UserStore.Get |  Avg| 10ms| 9ms | -1ms | -10.081
| |  P99| 138ms| 99ms | -39ms | -28.195
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 74ms | -10ms | -11.963
| UserStore.GetAllProfilesInChannel |  Avg| 334ms| 319ms | -15ms | -4.492
| |  P99| 1.903s| 1.531s | -372ms | -19.547
| UserStore.GetByUsername |  Avg| 13ms| 12ms | -1ms | -7.816
| |  P99| 172ms| 185ms | 13ms | 7.558
| UserStore.GetForLogin |  Avg| 9ms| 8ms | -1ms | -11.665
| |  P99| 97ms| 91ms | -6ms | -6.172
| UserStore.GetMany |  Avg| 11ms| 10ms | -1ms | -9.146
| |  P99| 140ms| 89ms | -51ms | -36.301
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 64ms| 157ms | 93ms | 144.913
| |  P99| 100ms| 493ms | 393ms | 394.975
| UserStore.GetProfileByIds |  Avg| 13ms| 11ms | -2ms | -15.672
| |  P99| 180ms| 143ms | -37ms | -20.560
| UserStore.GetProfilesByUsernames |  Avg| 14ms| 13ms | -1ms | -7.279
| |  P99| 185ms| 161ms | -24ms | -12.985
| UserStore.GetProfilesInChannel |  Avg| 26ms| 13ms | -13ms | -49.539
| |  P99| 435ms| 204ms | -231ms | -53.105
| UserStore.GetProfilesNotInChannel |  Avg| 17ms| 22ms | 5ms | 30.167
| |  P99| 96ms| 211ms | 115ms | 119.585
| UserStore.GetUnreadCount |  Avg| 9ms| 8ms | -1ms | -11.326
| |  P99| 105ms| 94ms | -11ms | -10.485
| UserStore.IsEmpty |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 45ms | -3ms | -6.303
| UserStore.Save |  Avg| 92ms| 90ms | -2ms | -2.180
| |  P99| 383ms| 339ms | -44ms | -11.498
| UserStore.Search |  Avg| 49ms| 48ms | -1ms | -2.028
| |  P99| 237ms| 234ms | -3ms | -1.263
| UserStore.Update |  Avg| 17ms| 23ms | 6ms | 34.292
| |  P99| 202ms| 230ms | 28ms | 13.861
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 88ms | -6ms | -6.398
| UserStore.UpdateLastLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 72ms| 65ms | -7ms | -9.738
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 74ms| 64ms | -10ms | -13.535
| UserTermsOfServiceStore.GetByUser |  Avg| 8ms| 7ms | -1ms | -13.026
| |  P99| 96ms| 91ms | -5ms | -5.206
| WebhookStore.GetOutgoingByTeam |  Avg| 14ms| 13ms | -1ms | -7.045
| |  P99| 184ms| 162ms | -22ms | -11.973
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 474ms| 409ms | -65ms | -13.707
| | P99| 2.362s| 2.037s | -325ms | -13.757
| addTeamMember | Avg| 1.295s| 1.209s | -86ms | -6.639
| | P99| 8.007s| 5.894s | -2.113s | -26.390
| autocompleteChannelsForTeamForSearch | Avg| 76ms| 42ms | -34ms | -44.809
| | P99| 262ms| 239ms | -23ms | -8.783
| autocompleteEmojis | Avg| 34ms| 0s | -34ms | -99.077
| | P99| 99ms| 0s | -99ms | -99.951
| autocompleteUsers | Avg| 67ms| 67ms | 0s | 0.000
| | P99| 381ms| 346ms | -35ms | -9.187
| channelMemberCountsByGroup | Avg| 18ms| 0s | -18ms | -98.939
| | P99| 212ms| 0s | -212ms | -99.766
| createChannel | Avg| 513ms| 483ms | -30ms | -5.853
| | P99| 2.155s| 4.35s | 2.195s | 101.858
| createChannelBookmark | Avg| 24ms| 26ms | 2ms | 8.438
| | P99| 93ms| 97ms | 4ms | 4.324
| createDirectChannel | Avg| 479ms| 455ms | -24ms | -5.005
| | P99| 2.443s| 2.297s | -146ms | -5.976
| createEmoji | Avg| 8ms| 0s | -8ms | -104.014
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 689ms| 721ms | 32ms | 4.646
| | P99| 3.925s| 3.86s | -65ms | -1.656
| createPost | Avg| 658ms| 603ms | -55ms | -8.354
| | P99| 4.24s| 3.566s | -674ms | -15.896
| createSchedulePost | Avg| 19ms| 20ms | 1ms | 5.228
| | P99| 207ms| 206ms | -1ms | -0.484
| createUser | Avg| 292ms| 278ms | -14ms | -4.796
| | P99| 1.983s| 1.706s | -277ms | -13.968
| deleteChannelBookmark | Avg| 37ms| 57ms | 20ms | 53.860
| | P99| 50ms| 99ms | 49ms | 98.459
| deleteDraft | Avg| 16ms| 14ms | -2ms | -12.580
| | P99| 205ms| 190ms | -15ms | -7.307
| deletePost | Avg| 79ms| 60ms | -19ms | -24.195
| | P99| 471ms| 244ms | -227ms | -48.170
| followThreadByUser | Avg| 56ms| 65ms | 9ms | 16.115
| | P99| 461ms| 810ms | 349ms | 75.663
| getAllTeams | Avg| 10ms| 9ms | -1ms | -9.819
| | P99| 153ms| 126ms | -27ms | -17.595
| getAnalytics | Avg| 176ms| 134ms | -42ms | -23.884
| | P99| 495ms| 247ms | -248ms | -50.101
| getCategoriesForTeamForUser | Avg| 32ms| 15ms | -17ms | -52.773
| | P99| 246ms| 194ms | -52ms | -21.143
| getChannel | Avg| 22ms| 23ms | 1ms | 4.581
| | P99| 221ms| 229ms | 8ms | 3.622
| getChannelMember | Avg| 19ms| 17ms | -2ms | -10.431
| | P99| 232ms| 217ms | -15ms | -6.464
| getChannelMembers | Avg| 20ms| 8ms | -12ms | -59.933
| | P99| 49ms| 25ms | -24ms | -48.607
| getChannelMembersForTeamForUser | Avg| 13ms| 12ms | -1ms | -7.413
| | P99| 175ms| 147ms | -28ms | -15.971
| getChannelMembersForUser | Avg| 10ms| 9ms | -1ms | -9.846
| | P99| 106ms| 95ms | -11ms | -10.421
| getChannelStats | Avg| 8ms| 7ms | -1ms | -12.282
| | P99| 169ms| 141ms | -28ms | -16.600
| getChannelUnread | Avg| 15ms| 14ms | -1ms | -6.647
| | P99| 218ms| 200ms | -18ms | -8.259
| getChannelsForTeamForUser | Avg| 14ms| 13ms | -1ms | -7.158
| | P99| 189ms| 167ms | -22ms | -11.651
| getChannelsForUser | Avg| 9ms| 8ms | -1ms | -10.983
| | P99| 100ms| 94ms | -6ms | -6.013
| getClientConfig | Avg| 20ms| 18ms | -2ms | -10.117
| | P99| 237ms| 229ms | -8ms | -3.375
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 15ms| 14ms | -1ms | -6.528
| | P99| 200ms| 180ms | -20ms | -10.014
| getFilePreview | Avg| 70ms| 67ms | -3ms | -4.289
| | P99| 440ms| 407ms | -33ms | -7.506
| getFileThumbnail | Avg| 60ms| 57ms | -3ms | -4.984
| | P99| 406ms| 354ms | -52ms | -12.817
| getFilteredUsersStats | Avg| 14ms| 54ms | 40ms | 293.329
| | P99| 25ms| 246ms | 221ms | 889.108
| getGroups | Avg| 12ms| 15ms | 3ms | 24.298
| | P99| 97ms| 98ms | 1ms | 1.030
| getGroupsAssociatedToChannelsByTeam | Avg| 78ms| 49ms | -29ms | -37.096
| | P99| 247ms| 99ms | -148ms | -59.919
| getPostThread | Avg| 62ms| 56ms | -6ms | -9.680
| | P99| 487ms| 458ms | -29ms | -5.959
| getPostsForChannel | Avg| 109ms| 91ms | -18ms | -16.556
| | P99| 1.257s| 896ms | -361ms | -28.728
| getPostsForChannelAroundLastUnread | Avg| 46ms| 42ms | -4ms | -8.725
| | P99| 454ms| 413ms | -41ms | -9.021
| getPreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 132ms| 108ms | -24ms | -18.251
| getPrevTrialLicense | Avg| 2ms| 8ms | 6ms | 324.474
| | P99| 5ms| 25ms | 20ms | 404.040
| getProductNotices | Avg| 9ms| 10ms | 1ms | 11.068
| | P99| 25ms| 25ms | 0s | 0.000
| getProfileImage | Avg| 91ms| 82ms | -9ms | -9.892
| | P99| 652ms| 496ms | -156ms | -23.911
| getPublicChannelsForTeam | Avg| 33ms| 30ms | -3ms | -9.132
| | P99| 224ms| 197ms | -27ms | -12.069
| getRolesByNames | Avg| 0s| 1ms | 1ms | 919.807
| | P99| 5ms| 9ms | 4ms | 80.808
| getServerLimits | Avg| 38ms| 17ms | -21ms | -54.787
| | P99| 99ms| 25ms | -74ms | -74.748
| getTeamMember | Avg| 11ms| 10ms | -1ms | -8.915
| | P99| 147ms| 143ms | -4ms | -2.728
| getTeamMembersForUser | Avg| 10ms| 9ms | -1ms | -10.430
| | P99| 128ms| 109ms | -19ms | -14.837
| getTeamScheduledPosts | Avg| 16ms| 15ms | -1ms | -6.084
| | P99| 216ms| 195ms | -21ms | -9.744
| getTeamStats | Avg| 88ms| 72ms | -16ms | -18.170
| | P99| 243ms| 242ms | -1ms | -0.411
| getTeamsForUser | Avg| 9ms| 8ms | -1ms | -11.328
| | P99| 100ms| 95ms | -5ms | -5.023
| getTeamsUnreadForUser | Avg| 17ms| 16ms | -1ms | -5.830
| | P99| 223ms| 207ms | -16ms | -7.191
| getThreadsForUser | Avg| 16ms| 15ms | -1ms | -6.300
| | P99| 201ms| 182ms | -19ms | -9.435
| getUser | Avg| 15ms| 13ms | -2ms | -13.203
| | P99| 231ms| 213ms | -18ms | -7.803
| getUserByUsername | Avg| 41ms| 15ms | -26ms | -63.363
| | P99| 245ms| 49ms | -196ms | -79.837
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 88ms| 73ms | -15ms | -17.105
| getUsers | Avg| 14ms| 12ms | -2ms | -14.511
| | P99| 224ms| 206ms | -18ms | -8.044
| getUsersByGroupChannelIds | Avg| 65ms| 149ms | 84ms | 129.944
| | P99| 100ms| 495ms | 395ms | 396.985
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 49ms| 45ms | -4ms | -8.096
| getUsersByNames | Avg| 14ms| 13ms | -1ms | -6.960
| | P99| 192ms| 171ms | -21ms | -10.917
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 72ms| 104ms | 32ms | 44.606
| | P99| 100ms| 247ms | 147ms | 147.739
| listCPAFields | Avg| 10ms| 9ms | -1ms | -10.454
| | P99| 130ms| 120ms | -10ms | -7.685
| listCPAValues | Avg| 15ms| 11ms | -4ms | -26.821
| | P99| 197ms| 113ms | -84ms | -42.659
| listChannelBookmarksForChannel | Avg| 11ms| 10ms | -1ms | -9.150
| | P99| 165ms| 136ms | -29ms | -17.601
| login | Avg| 118ms| 113ms | -5ms | -4.236
| | P99| 883ms| 795ms | -88ms | -9.962
| logout | Avg| 162ms| 126ms | -36ms | -22.218
| | P99| 885ms| 740ms | -145ms | -16.384
| patchPost | Avg| 82ms| 82ms | 0s | 0.000
| | P99| 777ms| 642ms | -135ms | -17.364
| removeUserCustomStatus | Avg| 275ms| 296ms | 21ms | 7.623
| | P99| 947ms| 976ms | 29ms | 3.062
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 38ms| 35ms | -3ms | -7.983
| | P99| 338ms| 264ms | -74ms | -21.874
| searchAllChannels | Avg| 51ms| 52ms | 1ms | 1.942
| | P99| 238ms| 241ms | 3ms | 1.262
| searchFilesInTeam | Avg| 9ms| 0s | -9ms | -105.014
| | P99| 10ms| 0s | -10ms | -100.463
| searchGroupChannels | Avg| 16ms| 14ms | -2ms | -12.331
| | P99| 195ms| 166ms | -29ms | -14.891
| searchPostsInTeam | Avg| 175ms| 178ms | 3ms | 1.713
| | P99| 2.289s| 2.35s | 61ms | 2.664
| searchUsers | Avg| 52ms| 50ms | -2ms | -3.877
| | P99| 240ms| 236ms | -4ms | -1.668
| setPostReminder | Avg| 86ms| 98ms | 12ms | 14.025
| | P99| 835ms| 815ms | -20ms | -2.395
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 58ms| 43ms | -15ms | -25.961
| | P99| 450ms| 368ms | -82ms | -18.212
| updateCategoriesForTeamForUser | Avg| 208ms| 134ms | -74ms | -35.530
| | P99| 1.945s| 835ms | -1.11s | -57.070
| updateChannelBookmark | Avg| 94ms| 18ms | -76ms | -80.645
| | P99| 950ms| 50ms | -900ms | -94.736
| updateChannelBookmarkSortOrder | Avg| 59ms| 20ms | -39ms | -66.233
| | P99| 99ms| 25ms | -74ms | -74.550
| updatePreferences | Avg| 36ms| 32ms | -4ms | -11.132
| | P99| 377ms| 354ms | -23ms | -6.096
| updateReadStateAllThreadsByUser | Avg| 4ms| 19ms | 15ms | 348.306
| | P99| 5ms| 49ms | 44ms | 888.796
| updateReadStateThreadByUser | Avg| 134ms| 121ms | -13ms | -9.705
| | P99| 899ms| 777ms | -122ms | -13.572
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 608ms| 584ms | -24ms | -3.949
| | P99| 2.363s| 2.314s | -49ms | -2.074
| upsertDraft | Avg| 17ms| 16ms | -1ms | -5.725
| | P99| 214ms| 200ms | -14ms | -6.548
| viewChannel | Avg| 52ms| 47ms | -5ms | -9.636
| | P99| 483ms| 451ms | -32ms | -6.630
