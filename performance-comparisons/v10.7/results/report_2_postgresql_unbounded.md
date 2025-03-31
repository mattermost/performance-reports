### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | avg | 1ms | 72ms | 71ms | 7971.70
| TeamStore.AnalyticsTeamCount | avg | 1ms | 19ms | 18ms | 3040.54
| PostStore.AnalyticsPostCountByTeam | avg | 1ms | 18ms | 17ms | 2076.67
| LicenseStore.GetAll | avg | 1ms | 12ms | 11ms | 1550.90
| TokenStore.Cleanup | avg | 5ms | 45ms | 40ms | 880.30
| CommandWebhookStore.Cleanup | avg | 7ms | 45ms | 38ms | 580.58
| SessionStore.GetSessionsExpired | avg | 7ms | 21ms | 14ms | 199.57
| UserStore.AnalyticsActiveCount | avg | 27ms | 68ms | 41ms | 153.88
| ChannelStore.AnalyticsCountAll | avg | 23ms | 47ms | 24ms | 105.71
| JobStore.UpdateOptimistically | avg | 10ms | 19ms | 9ms | 92.61
| PostPersistentNotificationStore.Get | avg | 8ms | 15ms | 7ms | 84.85
| RoleStore.ChannelHigherScopedPermissions | avg | 14ms | 26ms | 12ms | 82.83
| PluginStore.Get | avg | 19ms | 33ms | 14ms | 72.38
| ChannelStore.GetMembersForUserWithPagination | avg | 28ms | 47ms | 19ms | 68.20
| BotStore.Get | avg | 11ms | 18ms | 7ms | 65.19
| UserStore.Count | avg | 26ms | 41ms | 15ms | 57.72
| RoleStore.GetByNames | avg | 38ms | 53ms | 15ms | 39.34
| SessionStore.Remove | avg | 14ms | 19ms | 5ms | 35.36
| ProductNoticesStore.GetViews | avg | 66ms | 87ms | 21ms | 31.97
| ScheduledPostStore.CreateScheduledPost | avg | 19ms | 25ms | 6ms | 31.37
| PostStore.GetPostReminders | avg | 35ms | 46ms | 11ms | 31.15
| PostStore.AnalyticsPostCount | avg | 202ms | 256ms | 54ms | 26.75
| UserStore.GetProfilesNotInChannel | avg | 14ms | 17ms | 3ms | 21.75
| JobStore.UpdateStatus | avg | 11ms | 13ms | 2ms | 18.36
| ThreadStore.MarkAllAsReadByTeam | avg | 34ms | 39ms | 5ms | 14.81
| PluginStore.List | avg | 16ms | 18ms | 2ms | 12.26
| ChannelStore.CreateSidebarCategory | avg | 74ms | 83ms | 9ms | 12.17
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 245ms | 240ms | 4846.49
| TokenStore.Cleanup | p99 | 10ms | 244ms | 234ms | 2375.63
| CommandWebhookStore.Cleanup | p99 | 25ms | 244ms | 219ms | 892.05
| LicenseStore.GetAll | p99 | 5ms | 49ms | 44ms | 888.52
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 49ms | 44ms | 888.52
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 49ms | 44ms | 888.52
| PostPersistentNotificationStore.Get | p99 | 69ms | 360ms | 291ms | 418.75
| UserStore.AnalyticsActiveCount | p99 | 50ms | 245ms | 195ms | 393.94
| SessionStore.GetSessionsExpired | p99 | 48ms | 229ms | 181ms | 376.11
| ChannelStore.AnalyticsCountAll | p99 | 25ms | 99ms | 74ms | 297.71
| JobStore.UpdateOptimistically | p99 | 83ms | 230ms | 147ms | 177.12
| SessionStore.Remove | p99 | 88ms | 225ms | 137ms | 155.68
| BotStore.Get | p99 | 81ms | 198ms | 117ms | 143.56
| PluginStore.Get | p99 | 95ms | 232ms | 137ms | 143.46
| ChannelStore.GetMembersForUserWithPagination | p99 | 97ms | 235ms | 138ms | 142.27
| ThreadStore.MarkAllAsReadByTeam | p99 | 98ms | 236ms | 138ms | 140.82
| ChannelStore.CreateSidebarCategory | p99 | 242ms | 478ms | 236ms | 97.32
| PostStore.GetPostReminders | p99 | 231ms | 415ms | 184ms | 79.48
| ThreadStore.Get | p99 | 230ms | 321ms | 91ms | 39.59
| RoleStore.ChannelHigherScopedPermissions | p99 | 90ms | 121ms | 31ms | 34.25
| JobStore.UpdateStatus | p99 | 83ms | 111ms | 28ms | 33.53
| ScheduledPostStore.CreateScheduledPost | p99 | 173ms | 220ms | 47ms | 27.09
| PostPersistentNotificationStore.DeleteExpired | p99 | 158ms | 166ms | 8ms | 5.05
| FileInfoStore.AttachToPost | p99 | 239ms | 250ms | 11ms | 4.60
| UserStore.Count | p99 | 228ms | 238ms | 10ms | 4.38
| UserStore.GetProfilesNotInChannel | p99 | 92ms | 96ms | 4ms | 4.34
| ReactionStore.GetForPost | p99 | 198ms | 206ms | 8ms | 4.03
| RoleStore.GetByNames | p99 | 236ms | 245ms | 9ms | 3.81
| PostAcknowledgementStore.GetForPost | p99 | 168ms | 171ms | 3ms | 1.78
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 39ms | 0s | -39ms | -99.73
| ChannelStore.GetByNameIncludeDeleted | avg | 42ms | 0s | -42ms | -98.88
| ChannelStore.GetMembers | avg | 57ms | 2ms | -55ms | -96.53
| SchemeStore.GetAllPage | avg | 7ms | 3ms | -4ms | -58.29
| JobStore.GetNewestJobByStatusesAndType | avg | 29ms | 13ms | -16ms | -55.27
| JobStore.GetCountByStatusAndType | avg | 39ms | 18ms | -21ms | -54.14
| UserStore.GetProfilesInChannel | avg | 28ms | 14ms | -14ms | -50.43
| ChannelBookmarkStore.Get | avg | 34ms | 17ms | -17ms | -49.92
| ChannelBookmarkStore.Save | avg | 70ms | 37ms | -33ms | -47.22
| UserAccessTokenStore.GetByToken | avg | 24ms | 14ms | -10ms | -41.46
| UserStore.GetByUsername | avg | 30ms | 18ms | -12ms | -40.16
| ChannelStore.GetSidebarCategory | avg | 56ms | 34ms | -22ms | -39.41
| ScheduledPostStore.GetPendingScheduledPosts | avg | 41ms | 25ms | -16ms | -39.28
| JobStore.Save | avg | 26ms | 16ms | -10ms | -38.37
| UserStore.GetMany | avg | 21ms | 13ms | -8ms | -38.00
| StatusStore.SaveOrUpdate | avg | 43ms | 27ms | -16ms | -37.09
| PostStore.Delete | avg | 119ms | 75ms | -44ms | -36.95
| JobStore.GetAllByTypePage | avg | 34ms | 22ms | -12ms | -35.34
| FileInfoStore.GetForPost | avg | 23ms | 15ms | -8ms | -35.23
| ChannelStore.AutocompleteInTeamForSearch | avg | 119ms | 78ms | -41ms | -34.34
| ChannelStore.UpdateSidebarCategories | avg | 218ms | 147ms | -71ms | -32.64
| EmojiStore.GetMultipleByName | avg | 44ms | 30ms | -14ms | -31.93
| PreferenceStore.DeleteCategoryAndName | avg | 22ms | 15ms | -7ms | -31.36
| ChannelStore.Save | avg | 81ms | 56ms | -25ms | -30.96
| PostStore.GetPostsAfter | avg | 20ms | 14ms | -6ms | -29.87
| TeamStore.GetActiveMemberCount | avg | 97ms | 68ms | -29ms | -29.86
| EmojiStore.GetByName | avg | 18ms | 13ms | -5ms | -28.21
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 11ms | 8ms | -3ms | -28.16
| TeamStore.GetTotalMemberCount | avg | 85ms | 61ms | -24ms | -28.12
| LinkMetadataStore.Get | avg | 18ms | 13ms | -5ms | -28.04
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 15ms | 11ms | -4ms | -26.56
| ChannelStore.GetPinnedPostCount | avg | 19ms | 14ms | -5ms | -26.37
| PostPersistentNotificationStore.GetSingle | avg | 15ms | 11ms | -4ms | -26.33
| PostAcknowledgementStore.GetForPosts | avg | 27ms | 20ms | -7ms | -26.07
| ChannelStore.Get | avg | 39ms | 29ms | -10ms | -25.96
| PostStore.GetPostReminderMetadata | avg | 27ms | 20ms | -7ms | -25.89
| ThreadStore.Get | avg | 23ms | 17ms | -6ms | -25.77
| ChannelStore.GetPublicChannelsForTeam | avg | 39ms | 29ms | -10ms | -25.55
| FileInfoStore.SetContent | avg | 35ms | 26ms | -9ms | -25.51
| ThreadStore.GetTotalThreads | avg | 16ms | 12ms | -4ms | -25.42
| ThreadStore.GetTeamsUnreadForUser | avg | 24ms | 18ms | -6ms | -25.33
| PostPriorityStore.GetForPosts | avg | 28ms | 21ms | -7ms | -25.02
| TeamStore.Get | avg | 16ms | 12ms | -4ms | -24.51
| ChannelStore.GetChannelsByUser | avg | 25ms | 19ms | -6ms | -24.05
| UserStore.GetUnreadCount | avg | 17ms | 13ms | -4ms | -24.03
| PostStore.Get | avg | 46ms | 35ms | -11ms | -23.99
| ScheduledPostStore.GetScheduledPostsForUser | avg | 13ms | 10ms | -3ms | -23.84
| UserTermsOfServiceStore.GetByUser | avg | 13ms | 10ms | -3ms | -23.80
| ChannelStore.GetGuestCount | avg | 17ms | 13ms | -4ms | -23.34
| LinkMetadataStore.Save | avg | 13ms | 10ms | -3ms | -23.28
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 17ms | 13ms | -4ms | -23.24
| PostStore.GetSingle | avg | 17ms | 13ms | -4ms | -23.17
| ThreadStore.GetThreadsForUser | avg | 26ms | 20ms | -6ms | -23.09
| ChannelStore.SearchGroupChannels | avg | 27ms | 21ms | -6ms | -22.50
| DraftStore.Get | avg | 27ms | 21ms | -6ms | -22.30
| GroupStore.GetGroups | avg | 18ms | 14ms | -4ms | -22.19
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 18ms | 14ms | -4ms | -22.19
| ChannelBookmarkStore.Delete | avg | 50ms | 39ms | -11ms | -22.05
| ChannelStore.GetMembersForUser | avg | 23ms | 18ms | -5ms | -22.01
| ChannelStore.GetChannels | avg | 23ms | 18ms | -5ms | -22.00
| PreferenceStore.GetAll | avg | 18ms | 14ms | -4ms | -21.84
| UserStore.GetProfileByIds | avg | 23ms | 18ms | -5ms | -21.78
| ChannelStore.GetChannelUnread | avg | 23ms | 18ms | -5ms | -21.41
| ChannelStore.IsReadOnlyChannel | avg | 19ms | 15ms | -4ms | -21.32
| TeamStore.GetAllPage | avg | 14ms | 11ms | -3ms | -21.17
| WebhookStore.GetOutgoingByTeam | avg | 24ms | 19ms | -5ms | -21.14
| SessionStore.GetLRUSessions | avg | 10ms | 8ms | -2ms | -20.99
| ThreadStore.GetMembershipForUser | avg | 19ms | 15ms | -4ms | -20.91
| ChannelStore.GetMemberForPost | avg | 29ms | 23ms | -6ms | -20.87
| PostStore.SearchPostsForUser | avg | 77ms | 61ms | -16ms | -20.78
| PreferenceStore.Get | avg | 19ms | 15ms | -4ms | -20.61
| PostStore.SetPostReminder | avg | 51ms | 41ms | -10ms | -19.76
| TeamStore.GetTeamsByUserId | avg | 15ms | 12ms | -3ms | -19.58
| ThreadStore.GetThreadForUser | avg | 31ms | 25ms | -6ms | -19.33
| SharedChannelStore.HasChannel | avg | 16ms | 13ms | -3ms | -19.18
| TeamStore.GetChannelUnreadsForAllTeams | avg | 16ms | 13ms | -3ms | -18.77
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 16ms | 13ms | -3ms | -18.75
| PostStore.GetEtag | avg | 21ms | 17ms | -4ms | -18.73
| StatusStore.Get | avg | 16ms | 13ms | -3ms | -18.48
| ThreadStore.GetTotalUnreadMentions | avg | 16ms | 13ms | -3ms | -18.35
| UserStore.GetProfilesByUsernames | avg | 22ms | 18ms | -4ms | -18.31
| ThreadStore.GetThreadFollowers | avg | 16ms | 13ms | -3ms | -18.19
| ThreadStore.MarkAllAsReadByChannels | avg | 17ms | 14ms | -3ms | -18.14
| ChannelBookmarkStore.UpdateSortOrder | avg | 67ms | 55ms | -12ms | -17.96
| PostStore.GetPosts | avg | 11ms | 9ms | -2ms | -17.82
| UserStore.Get | avg | 17ms | 14ms | -3ms | -17.69
| JobStore.GetAllByStatus | avg | 23ms | 19ms | -4ms | -17.68
| ChannelStore.GetMemberLastViewedAt | avg | 11ms | 9ms | -2ms | -17.45
| PostStore.GetPostsBefore | avg | 23ms | 19ms | -4ms | -17.13
| UserStore.GetAllProfiles | avg | 12ms | 10ms | -2ms | -17.08
| StatusStore.GetByIds | avg | 29ms | 24ms | -5ms | -17.07
| PostStore.GetPostsByThread | avg | 24ms | 20ms | -4ms | -16.83
| PostAcknowledgementStore.GetForPost | avg | 12ms | 10ms | -2ms | -16.52
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 42ms | 35ms | -7ms | -16.48
| PostStore.GetPostsSince | avg | 38ms | 32ms | -6ms | -15.97
| PostPriorityStore.GetForPost | avg | 13ms | 11ms | -2ms | -15.02
| ChannelStore.GetAllChannelMembersForUser | avg | 20ms | 17ms | -3ms | -15.00
| ThreadStore.GetThreadUnreadReplyCount | avg | 27ms | 23ms | -4ms | -14.95
| FileInfoStore.Get | avg | 20ms | 17ms | -3ms | -14.80
| ChannelStore.SaveMember | avg | 90ms | 77ms | -13ms | -14.43
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 35ms | 30ms | -5ms | -14.42
| TeamStore.GetTeamsForUser | avg | 14ms | 12ms | -2ms | -14.33
| FileInfoStore.GetByIds | avg | 21ms | 18ms | -3ms | -14.14
| PostStore.GetPostIdBeforeTime | avg | 15ms | 13ms | -2ms | -13.41
| ChannelStore.GetByName | avg | 15ms | 13ms | -2ms | -13.39
| ThreadStore.UpdateMembership | avg | 15ms | 13ms | -2ms | -13.35
| FileInfoStore.Save | avg | 23ms | 20ms | -3ms | -13.23
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 15ms | 13ms | -2ms | -13.09
| ThreadStore.GetTotalUnreadThreads | avg | 15ms | 13ms | -2ms | -12.92
| StatusStore.UpdateLastActivityAt | avg | 16ms | 14ms | -2ms | -12.89
| SessionStore.UpdateLastActivityAt | avg | 16ms | 14ms | -2ms | -12.81
| DraftStore.GetDraftsForUser | avg | 25ms | 22ms | -3ms | -11.84
| ChannelStore.GetMember | avg | 17ms | 15ms | -2ms | -11.68
| SessionStore.Get | avg | 26ms | 23ms | -3ms | -11.67
| ThreadStore.MaintainMembership | avg | 35ms | 31ms | -4ms | -11.47
| ChannelStore.GetFileCount | avg | 18ms | 16ms | -2ms | -10.98
| ChannelStore.CreateInitialSidebarCategories | avg | 77ms | 69ms | -8ms | -10.34
| ChannelStore.CreateDirectChannel | avg | 127ms | 114ms | -13ms | -10.26
| UserStore.Search | avg | 59ms | 53ms | -6ms | -10.18
| PluginStore.SetWithOptions | avg | 20ms | 18ms | -2ms | -10.12
| PostStore.Save | avg | 59ms | 53ms | -6ms | -10.09
| ChannelStore.GetMemberCount | avg | 41ms | 37ms | -4ms | -9.70
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 21ms | 19ms | -2ms | -9.65
| SessionStore.Save | avg | 21ms | 19ms | -2ms | -9.59
| DraftStore.Upsert | avg | 21ms | 19ms | -2ms | -9.43
| UserStore.GetAllProfilesInChannel | avg | 434ms | 397ms | -37ms | -8.52
| ChannelStore.Autocomplete | avg | 61ms | 56ms | -5ms | -8.20
| StatusStore.UpdateExpiredDNDStatuses | avg | 25ms | 23ms | -2ms | -8.16
| UserStore.AutocompleteUsersInChannel | avg | 88ms | 81ms | -7ms | -7.99
| UserStore.Update | avg | 41ms | 38ms | -3ms | -7.23
| PreferenceStore.Save | avg | 42ms | 39ms | -3ms | -7.09
| TeamStore.SaveMember | avg | 58ms | 54ms | -4ms | -6.92
| FileInfoStore.AttachToPost | avg | 30ms | 28ms | -2ms | -6.65
| ProductNoticesStore.View | avg | 112ms | 109ms | -3ms | -2.67
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 230ms | 0s | -230ms | -99.78
| ChannelStore.GetMembers | p99 | 243ms | 5ms | -238ms | -98.14
| ChannelBookmarkStore.Get | p99 | 427ms | 97ms | -330ms | -77.20
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.727s | 541ms | -1.186s | -68.66
| JobStore.GetCountByStatusAndType | p99 | 713ms | 263ms | -450ms | -63.16
| UserStore.GetProfilesInChannel | p99 | 234ms | 92ms | -142ms | -60.72
| EmojiStore.GetMultipleByName | p99 | 244ms | 96ms | -148ms | -60.66
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 195ms | 83ms | -112ms | -57.58
| JobStore.GetNewestJobByStatusesAndType | p99 | 478ms | 216ms | -262ms | -54.87
| PostStore.Delete | p99 | 912ms | 430ms | -482ms | -52.82
| TeamStore.GetTotalMemberCount | p99 | 461ms | 227ms | -234ms | -50.73
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 454ms | 224ms | -230ms | -50.69
| SchemeStore.GetAllPage | p99 | 10ms | 5ms | -5ms | -50.25
| StatusStore.SaveOrUpdate | p99 | 669ms | 335ms | -334ms | -49.91
| PreferenceStore.DeleteCategoryAndName | p99 | 412ms | 208ms | -204ms | -49.46
| ChannelBookmarkStore.Delete | p99 | 470ms | 240ms | -230ms | -48.94
| UserStore.GetByUsername | p99 | 410ms | 216ms | -194ms | -47.28
| StatusStore.UpdateExpiredDNDStatuses | p99 | 408ms | 217ms | -191ms | -46.87
| PostStore.SetPostReminder | p99 | 435ms | 233ms | -202ms | -46.44
| TeamStore.GetActiveMemberCount | p99 | 422ms | 235ms | -187ms | -44.26
| ChannelStore.GetPublicChannelsForTeam | p99 | 371ms | 211ms | -160ms | -43.11
| ChannelBookmarkStore.Save | p99 | 405ms | 233ms | -172ms | -42.47
| ChannelStore.UpdateSidebarCategories | p99 | 2.005s | 1.195s | -810ms | -40.40
| PostStore.SearchPostsForUser | p99 | 2.071s | 1.269s | -802ms | -38.73
| ChannelStore.Save | p99 | 723ms | 444ms | -279ms | -38.57
| FileInfoStore.SetContent | p99 | 363ms | 224ms | -139ms | -38.32
| ChannelStore.Get | p99 | 435ms | 287ms | -148ms | -34.03
| ThreadStore.GetThreadForUser | p99 | 407ms | 274ms | -133ms | -32.65
| TeamStore.GetMember | p99 | 165ms | 112ms | -53ms | -32.08
| PostPriorityStore.GetForPosts | p99 | 454ms | 314ms | -140ms | -30.86
| ThreadStore.GetTeamsUnreadForUser | p99 | 344ms | 238ms | -106ms | -30.83
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 190ms | 132ms | -58ms | -30.49
| PostAcknowledgementStore.GetForPosts | p99 | 449ms | 312ms | -137ms | -30.48
| UserStore.Search | p99 | 355ms | 247ms | -108ms | -30.42
| StatusStore.GetByIds | p99 | 343ms | 242ms | -101ms | -29.47
| UserStore.GetAllProfiles | p99 | 190ms | 134ms | -56ms | -29.44
| FileInfoStore.GetByIds | p99 | 318ms | 228ms | -90ms | -28.29
| ChannelStore.SearchGroupChannels | p99 | 316ms | 227ms | -89ms | -28.13
| JobStore.Save | p99 | 250ms | 180ms | -70ms | -28.00
| ChannelStore.GetMemberForPost | p99 | 326ms | 236ms | -90ms | -27.60
| PostStore.GetPosts | p99 | 178ms | 129ms | -49ms | -27.56
| DraftStore.Get | p99 | 320ms | 236ms | -84ms | -26.29
| FileInfoStore.GetForPost | p99 | 290ms | 214ms | -76ms | -26.19
| ChannelStore.GetMemberLastViewedAt | p99 | 196ms | 145ms | -51ms | -25.99
| UserStore.GetMany | p99 | 249ms | 185ms | -64ms | -25.65
| SessionStore.GetLRUSessions | p99 | 164ms | 122ms | -42ms | -25.63
| PostStore.GetPostsSince | p99 | 320ms | 240ms | -80ms | -24.97
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 474ms | 365ms | -109ms | -22.97
| PostStore.Get | p99 | 476ms | 369ms | -107ms | -22.48
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 206ms | 161ms | -45ms | -21.81
| ChannelStore.GetSidebarCategory | p99 | 456ms | 360ms | -96ms | -21.06
| ThreadStore.MarkAsRead | p99 | 158ms | 125ms | -33ms | -20.93
| ThreadStore.UpdateMembership | p99 | 153ms | 121ms | -32ms | -20.85
| EmojiStore.GetByName | p99 | 235ms | 186ms | -49ms | -20.85
| ThreadStore.GetThreadsForUser | p99 | 286ms | 228ms | -58ms | -20.29
| ThreadStore.MaintainMembership | p99 | 343ms | 274ms | -69ms | -20.14
| PostStore.GetPostsAfter | p99 | 239ms | 191ms | -48ms | -20.05
| PostPersistentNotificationStore.GetSingle | p99 | 230ms | 184ms | -46ms | -20.00
| SystemStore.GetByName | p99 | 161ms | 129ms | -32ms | -19.92
| TeamStore.Get | p99 | 236ms | 189ms | -47ms | -19.91
| ChannelStore.SaveMember | p99 | 920ms | 746ms | -174ms | -18.92
| UserTermsOfServiceStore.GetByUser | p99 | 208ms | 169ms | -39ms | -18.76
| PostStore.GetSingle | p99 | 239ms | 196ms | -43ms | -17.99
| ChannelStore.GetByName | p99 | 214ms | 177ms | -37ms | -17.32
| ThreadStore.GetTotalUnreadMentions | p99 | 233ms | 193ms | -40ms | -17.19
| GroupStore.GetGroups | p99 | 237ms | 197ms | -40ms | -16.88
| ThreadStore.GetThreadFollowers | p99 | 238ms | 198ms | -40ms | -16.81
| TeamStore.GetAllPage | p99 | 221ms | 184ms | -37ms | -16.72
| LinkMetadataStore.Get | p99 | 241ms | 201ms | -40ms | -16.62
| StatusStore.UpdateLastActivityAt | p99 | 170ms | 142ms | -28ms | -16.49
| ChannelStore.GetGuestCount | p99 | 231ms | 193ms | -38ms | -16.42
| ChannelStore.Autocomplete | p99 | 339ms | 284ms | -55ms | -16.24
| SessionStore.UpdateLastActivityAt | p99 | 167ms | 140ms | -27ms | -16.17
| UserStore.GetUnreadCount | p99 | 235ms | 197ms | -38ms | -16.17
| ThreadStore.GetTotalThreads | p99 | 226ms | 190ms | -36ms | -15.90
| ChannelStore.UpdateLastViewedAt | p99 | 163ms | 137ms | -26ms | -15.90
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 233ms | 196ms | -37ms | -15.85
| ChannelStore.GetPinnedPostCount | p99 | 242ms | 204ms | -38ms | -15.69
| TeamStore.GetTeamsByUserId | p99 | 225ms | 190ms | -35ms | -15.56
| UserStore.GetForLogin | p99 | 189ms | 160ms | -29ms | -15.31
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 231ms | 196ms | -35ms | -15.13
| UserStore.Update | p99 | 359ms | 305ms | -54ms | -15.04
| LinkMetadataStore.Save | p99 | 87ms | 74ms | -13ms | -14.94
| SharedChannelStore.HasChannel | p99 | 221ms | 188ms | -33ms | -14.92
| PostStore.GetPostsByThread | p99 | 239ms | 204ms | -35ms | -14.62
| TeamStore.GetTeamsForUser | p99 | 212ms | 181ms | -31ms | -14.60
| ThreadStore.GetTotalUnreadThreads | p99 | 226ms | 193ms | -33ms | -14.58
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 227ms | 194ms | -33ms | -14.54
| GroupStore.GetByName | p99 | 180ms | 154ms | -26ms | -14.43
| ThreadStore.GetMembershipForUser | p99 | 245ms | 211ms | -34ms | -13.90
| StatusStore.Get | p99 | 232ms | 200ms | -32ms | -13.82
| UserStore.Get | p99 | 225ms | 194ms | -31ms | -13.76
| PreferenceStore.GetAll | p99 | 233ms | 201ms | -32ms | -13.75
| JobStore.GetAllByStatus | p99 | 274ms | 237ms | -37ms | -13.49
| ThreadStore.MarkAllAsReadByChannels | p99 | 186ms | 161ms | -25ms | -13.42
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 224ms | 194ms | -30ms | -13.41
| UserStore.IsEmpty | p99 | 85ms | 74ms | -11ms | -12.92
| TeamStore.SaveMember | p99 | 458ms | 400ms | -58ms | -12.66
| SessionStore.Get | p99 | 274ms | 240ms | -34ms | -12.40
| ChannelStore.GetFileCount | p99 | 226ms | 198ms | -28ms | -12.38
| ChannelStore.IncrementMentionCount | p99 | 180ms | 158ms | -22ms | -12.23
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 430ms | 378ms | -52ms | -12.11
| PreferenceStore.Get | p99 | 240ms | 211ms | -29ms | -12.07
| ChannelStore.IsReadOnlyChannel | p99 | 235ms | 208ms | -27ms | -11.51
| ChannelStore.CreateInitialSidebarCategories | p99 | 813ms | 720ms | -93ms | -11.44
| UserStore.UpdateFailedPasswordAttempts | p99 | 144ms | 128ms | -16ms | -11.14
| AuditStore.Save | p99 | 144ms | 128ms | -16ms | -11.10
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 219ms | 195ms | -24ms | -10.98
| ChannelStore.GetChannelUnread | p99 | 250ms | 223ms | -27ms | -10.81
| PostStore.GetPostIdBeforeTime | p99 | 177ms | 158ms | -19ms | -10.76
| ChannelStore.GetAllChannelMembersForUser | p99 | 225ms | 201ms | -24ms | -10.68
| FileInfoStore.Save | p99 | 218ms | 196ms | -22ms | -10.09
| ChannelStore.GetMembersForUser | p99 | 248ms | 223ms | -25ms | -10.09
| ThreadStore.GetThreadUnreadReplyCount | p99 | 241ms | 217ms | -24ms | -9.97
| UserStore.GetProfileByIds | p99 | 246ms | 222ms | -24ms | -9.76
| ChannelStore.GetChannels | p99 | 248ms | 224ms | -24ms | -9.68
| FileInfoStore.Get | p99 | 241ms | 218ms | -23ms | -9.56
| PostStore.GetEtag | p99 | 245ms | 222ms | -23ms | -9.40
| PreferenceStore.Save | p99 | 397ms | 360ms | -37ms | -9.33
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 174ms | 158ms | -16ms | -9.21
| PostPriorityStore.GetForPost | p99 | 220ms | 200ms | -20ms | -9.08
| PostStore.GetPostsBefore | p99 | 246ms | 224ms | -22ms | -8.95
| ChannelStore.GetChannelsByUser | p99 | 248ms | 226ms | -22ms | -8.85
| UserStore.AutocompleteUsersInChannel | p99 | 475ms | 433ms | -42ms | -8.85
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 94ms | 86ms | -8ms | -8.50
| ChannelStore.GetMember | p99 | 200ms | 183ms | -17ms | -8.48
| WebhookStore.GetOutgoingByTeam | p99 | 248ms | 227ms | -21ms | -8.45
| UserStore.GetProfilesByUsernames | p99 | 242ms | 222ms | -20ms | -8.28
| PostStore.Update | p99 | 270ms | 248ms | -22ms | -8.15
| PluginStore.SetWithOptions | p99 | 218ms | 202ms | -16ms | -7.35
| JobStore.GetAllByTypePage | p99 | 221ms | 206ms | -15ms | -6.77
| PostStore.Save | p99 | 484ms | 454ms | -30ms | -6.20
| ClusterDiscoveryStore.SetLastPingAt | p99 | 243ms | 228ms | -15ms | -6.18
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 99ms | 93ms | -6ms | -6.08
| PostStore.GetPostIdAfterTime | p99 | 100ms | 94ms | -6ms | -6.01
| SessionStore.Save | p99 | 234ms | 220ms | -14ms | -5.99
| ChannelStore.GetMemberCount | p99 | 250ms | 236ms | -14ms | -5.61
| PluginStore.Delete | p99 | 97ms | 92ms | -5ms | -5.14
| UserAccessTokenStore.GetByToken | p99 | 223ms | 212ms | -11ms | -4.92
| DraftStore.Upsert | p99 | 211ms | 201ms | -10ms | -4.74
| DraftStore.GetDraftsForUser | p99 | 247ms | 236ms | -11ms | -4.46
| UserStore.GetAllProfilesInChannel | p99 | 2.328s | 2.248s | -80ms | -3.44
| UserStore.UpdateUpdateAt | p99 | 98ms | 95ms | -3ms | -3.07
| PluginStore.List | p99 | 221ms | 215ms | -6ms | -2.71
| DraftStore.Delete | p99 | 196ms | 191ms | -5ms | -2.55
| ProductNoticesStore.View | p99 | 911ms | 890ms | -21ms | -2.31
| JobStore.UpdateStatusOptimistically | p99 | 90ms | 88ms | -2ms | -2.22
| ChannelStore.CreateDirectChannel | p99 | 947ms | 937ms | -10ms | -1.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | avg | 1ms | 36ms | 35ms | 6772.17
| getFilteredUsersStats | avg | 29ms | 135ms | 106ms | 365.65
| getRolesByNames | avg | 2ms | 4ms | 2ms | 96.25
| updateReadStateAllThreadsByUser | avg | 34ms | 60ms | 26ms | 76.74
| createSchedulePost | avg | 26ms | 35ms | 9ms | 35.04
| getUserByUsername | avg | 61ms | 73ms | 12ms | 19.81
| followThreadByUser | avg | 103ms | 107ms | 4ms | 3.88
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 5ms | 50ms | 45ms | 908.72
| getRolesByNames | p99 | 5ms | 47ms | 42ms | 848.48
| getFilteredUsersStats | p99 | 50ms | 247ms | 197ms | 395.98
| updateReadStateAllThreadsByUser | p99 | 98ms | 477ms | 379ms | 386.73
| getUserByUsername | p99 | 100ms | 247ms | 147ms | 147.71
| logout | p99 | 970ms | 2.132s | 1.162s | 119.79
| createSchedulePost | p99 | 249ms | 500ms | 251ms | 100.64
| createCategoryForTeamForUser | p99 | 242ms | 478ms | 236ms | 97.32
| followThreadByUser | p99 | 480ms | 765ms | 285ms | 59.32
| createChannel | p99 | 4.225s | 4.612s | 387ms | 9.16
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 55ms | 0s | -55ms | -99.56
| getChannelMembers | avg | 58ms | 2ms | -56ms | -97.12
| createEmoji | avg | 5ms | 0s | -5ms | -92.25
| updateChannelBookmark | avg | 203ms | 122ms | -81ms | -39.85
| createChannelBookmark | avg | 100ms | 61ms | -39ms | -38.89
| getJobsByType | avg | 34ms | 21ms | -13ms | -37.88
| setPostReminder | avg | 149ms | 95ms | -54ms | -36.14
| updateCategoriesForTeamForUser | avg | 349ms | 224ms | -125ms | -35.81
| autocompleteChannelsForTeamForSearch | avg | 120ms | 79ms | -41ms | -34.25
| deletePost | avg | 193ms | 127ms | -66ms | -34.14
| getTeamStats | avg | 109ms | 74ms | -35ms | -32.13
| getChannel | avg | 50ms | 35ms | -15ms | -29.88
| getPostThread | avg | 114ms | 82ms | -32ms | -28.18
| getPublicChannelsForTeam | avg | 41ms | 30ms | -11ms | -27.14
| getPreferences | avg | 19ms | 14ms | -5ms | -25.74
| getPostsForChannel | avg | 211ms | 157ms | -54ms | -25.58
| getTeamsForUser | avg | 16ms | 12ms | -4ms | -25.57
| getUser | avg | 32ms | 24ms | -8ms | -24.84
| createGroupChannel | avg | 1.216s | 925ms | -291ms | -23.92
| getChannelsForUser | avg | 25ms | 19ms | -6ms | -23.61
| getTeamScheduledPosts | avg | 26ms | 20ms | -6ms | -23.49
| getTeamsUnreadForUser | avg | 30ms | 23ms | -7ms | -23.24
| getChannelUnread | avg | 26ms | 20ms | -6ms | -22.94
| searchGroupChannels | avg | 27ms | 21ms | -6ms | -22.10
| getThreadsForUser | avg | 27ms | 21ms | -6ms | -22.07
| deleteDraft | avg | 28ms | 22ms | -6ms | -21.31
| getUsers | avg | 28ms | 22ms | -6ms | -21.24
| viewChannel | avg | 98ms | 78ms | -20ms | -20.34
| saveReaction | avg | 66ms | 53ms | -13ms | -19.80
| unfollowThreadByUser | avg | 98ms | 79ms | -19ms | -19.46
| removeUserCustomStatus | avg | 452ms | 368ms | -84ms | -18.60
| getPostsForChannelAroundLastUnread | avg | 76ms | 62ms | -14ms | -18.54
| updateReadStateThreadByUser | avg | 217ms | 177ms | -40ms | -18.44
| getAllTeams | avg | 17ms | 14ms | -3ms | -17.89
| searchPostsInTeam | avg | 118ms | 97ms | -21ms | -17.73
| getUsersByNames | avg | 23ms | 19ms | -4ms | -17.66
| createDirectChannel | avg | 718ms | 592ms | -126ms | -17.54
| getChannelMembersForTeamForUser | avg | 23ms | 19ms | -4ms | -17.11
| listChannelBookmarksForChannel | avg | 18ms | 15ms | -3ms | -17.10
| getChannelsForTeamForUser | avg | 23ms | 19ms | -4ms | -17.03
| getCategoriesForTeamForUser | avg | 43ms | 36ms | -7ms | -16.19
| getChannelMember | avg | 39ms | 33ms | -6ms | -15.38
| patchPost | avg | 151ms | 129ms | -22ms | -14.52
| getTeamMember | avg | 21ms | 18ms | -3ms | -14.25
| createChannel | avg | 943ms | 818ms | -125ms | -13.26
| logout | avg | 228ms | 199ms | -29ms | -12.73
| createPost | avg | 976ms | 855ms | -121ms | -12.40
| updatePreferences | avg | 66ms | 58ms | -8ms | -12.14
| getTeamMembersForUser | avg | 17ms | 15ms | -2ms | -11.44
| getClientConfig | avg | 36ms | 32ms | -4ms | -11.10
| addChannelMember | avg | 698ms | 621ms | -77ms | -11.04
| getDrafts | avg | 27ms | 24ms | -3ms | -11.01
| upsertDraft | avg | 28ms | 25ms | -3ms | -10.54
| searchUsers | avg | 61ms | 55ms | -6ms | -9.84
| addTeamMember | avg | 1.703s | 1.537s | -166ms | -9.75
| searchAllChannels | avg | 63ms | 57ms | -6ms | -9.60
| autocompleteUsers | avg | 84ms | 76ms | -8ms | -9.54
| getFileThumbnail | avg | 75ms | 69ms | -6ms | -7.99
| updateChannelBookmarkSortOrder | avg | 86ms | 80ms | -6ms | -7.01
| login | avg | 152ms | 144ms | -8ms | -5.26
| getFilePreview | avg | 85ms | 81ms | -4ms | -4.69
| getProfileImage | avg | 72ms | 69ms | -3ms | -4.15
| createUser | avg | 326ms | 313ms | -13ms | -3.98
| uploadFileStream | avg | 585ms | 578ms | -7ms | -1.20
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| channelMemberCountsByGroup | p99 | 243ms | 0s | -243ms | -99.80
| getChannelMembers | p99 | 243ms | 5ms | -238ms | -98.14
| deleteChannelBookmark | p99 | 980ms | 249ms | -731ms | -74.59
| updateChannelBookmark | p99 | 960ms | 248ms | -712ms | -74.17
| setPostReminder | p99 | 1.72s | 480ms | -1.24s | -72.09
| createChannelBookmark | p99 | 855ms | 242ms | -613ms | -71.70
| autocompleteChannelsForTeamForSearch | p99 | 1.727s | 541ms | -1.186s | -68.66
| deletePost | p99 | 1.975s | 860ms | -1.115s | -56.46
| getTeamStats | p99 | 474ms | 241ms | -233ms | -49.14
| patchPost | p99 | 1.911s | 986ms | -925ms | -48.41
| createGroupChannel | p99 | 8.339s | 4.391s | -3.948s | -47.35
| getPostThread | p99 | 1.574s | 871ms | -703ms | -44.66
| getPublicChannelsForTeam | p99 | 371ms | 213ms | -158ms | -42.57
| getChannel | p99 | 689ms | 406ms | -283ms | -41.07
| saveReaction | p99 | 800ms | 486ms | -314ms | -39.24
| getTeamScheduledPosts | p99 | 371ms | 246ms | -125ms | -33.66
| getPostsForChannel | p99 | 3.268s | 2.197s | -1.071s | -32.77
| searchUsers | p99 | 369ms | 248ms | -121ms | -32.76
| searchGroupChannels | p99 | 331ms | 229ms | -102ms | -30.78
| createPost | p99 | 7.026s | 4.864s | -2.162s | -30.77
| getThreadsForUser | p99 | 335ms | 236ms | -99ms | -29.59
| deleteDraft | p99 | 340ms | 240ms | -100ms | -29.44
| getTeamsUnreadForUser | p99 | 433ms | 312ms | -121ms | -27.94
| getChannelUnread | p99 | 316ms | 234ms | -82ms | -25.93
| createDirectChannel | p99 | 3.3s | 2.462s | -838ms | -25.40
| getPostsForChannelAroundLastUnread | p99 | 952ms | 730ms | -222ms | -23.31
| getUser | p99 | 451ms | 356ms | -95ms | -21.08
| updateReadStateThreadByUser | p99 | 2.182s | 1.725s | -457ms | -20.94
| getCategoriesForTeamForUser | p99 | 478ms | 378ms | -100ms | -20.93
| searchPostsInTeam | p99 | 2.432s | 1.94s | -492ms | -20.23
| getUserStatusesByIds | p99 | 179ms | 144ms | -35ms | -19.59
| getUsers | p99 | 421ms | 343ms | -78ms | -18.53
| viewChannel | p99 | 988ms | 818ms | -170ms | -17.22
| getChannelMember | p99 | 454ms | 382ms | -72ms | -15.85
| searchAllChannels | p99 | 365ms | 308ms | -57ms | -15.60
| getDrafts | p99 | 296ms | 250ms | -46ms | -15.56
| login | p99 | 1.56s | 1.32s | -240ms | -15.38
| getTeamsForUser | p99 | 228ms | 193ms | -35ms | -15.36
| getChannelsForUser | p99 | 267ms | 228ms | -39ms | -14.62
| getUsersByIds | p99 | 86ms | 74ms | -12ms | -13.91
| updateCategoriesForTeamForUser | p99 | 2.377s | 2.07s | -307ms | -12.91
| getPreferences | p99 | 241ms | 210ms | -31ms | -12.87
| getAllTeams | p99 | 239ms | 211ms | -28ms | -11.72
| getClientConfig | p99 | 381ms | 340ms | -41ms | -10.76
| unfollowThreadByUser | p99 | 925ms | 827ms | -98ms | -10.60
| getChannelMembersForTeamForUser | p99 | 251ms | 226ms | -25ms | -9.97
| getChannelsForTeamForUser | p99 | 252ms | 228ms | -24ms | -9.54
| autocompleteUsers | p99 | 491ms | 445ms | -46ms | -9.37
| getChannelStats | p99 | 210ms | 191ms | -19ms | -9.05
| listChannelBookmarksForChannel | p99 | 236ms | 215ms | -21ms | -8.90
| getTeamMember | p99 | 223ms | 205ms | -18ms | -8.08
| getUsersByNames | p99 | 245ms | 226ms | -19ms | -7.77
| removeUserCustomStatus | p99 | 2.357s | 2.182s | -175ms | -7.42
| getFileThumbnail | p99 | 481ms | 446ms | -35ms | -7.27
| getJobsByType | p99 | 221ms | 207ms | -14ms | -6.32
| getTeamMembersForUser | p99 | 235ms | 221ms | -14ms | -5.95
| addTeamMember | p99 | 10s | 9.483s | -517ms | -5.17
| addChannelMember | p99 | 4.253s | 4.059s | -194ms | -4.56
| upsertDraft | p99 | 248ms | 237ms | -11ms | -4.44
| getFilePreview | p99 | 492ms | 472ms | -20ms | -4.07
| createUser | p99 | 2.295s | 2.231s | -64ms | -2.79
| updatePreferences | p99 | 471ms | 461ms | -10ms | -2.12
| getProfileImage | p99 | 479ms | 471ms | -8ms | -1.67
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 144ms| 128ms | -16ms | -11.098
| BotStore.Get |  Avg| 11ms| 18ms | 7ms | 65.190
| |  P99| 81ms| 198ms | 117ms | 143.558
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -127.569
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 50ms| 39ms | -11ms | -22.045
| |  P99| 470ms| 240ms | -230ms | -48.936
| ChannelBookmarkStore.Get |  Avg| 34ms| 17ms | -17ms | -49.923
| |  P99| 427ms| 97ms | -330ms | -77.195
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 15ms| 13ms | -2ms | -13.088
| |  P99| 219ms| 195ms | -24ms | -10.983
| ChannelBookmarkStore.Save |  Avg| 70ms| 37ms | -33ms | -47.215
| |  P99| 405ms| 233ms | -172ms | -42.470
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 67ms| 55ms | -12ms | -17.960
| |  P99| 244ms| 245ms | 1ms | 0.410
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 11ms| 10ms | -1ms | -9.062
| |  P99| 99ms| 93ms | -6ms | -6.076
| ChannelStore.AnalyticsCountAll |  Avg| 23ms| 47ms | 24ms | 105.708
| |  P99| 25ms| 99ms | 74ms | 297.714
| ChannelStore.Autocomplete |  Avg| 61ms| 56ms | -5ms | -8.203
| |  P99| 339ms| 284ms | -55ms | -16.239
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 119ms| 78ms | -41ms | -34.335
| |  P99| 1.727s| 541ms | -1.186s | -68.655
| ChannelStore.CreateDirectChannel |  Avg| 127ms| 114ms | -13ms | -10.260
| |  P99| 947ms| 937ms | -10ms | -1.056
| ChannelStore.CreateInitialSidebarCategories |  Avg| 77ms| 69ms | -8ms | -10.343
| |  P99| 813ms| 720ms | -93ms | -11.439
| ChannelStore.CreateSidebarCategory |  Avg| 74ms| 83ms | 9ms | 12.175
| |  P99| 242ms| 478ms | 236ms | 97.320
| ChannelStore.Get |  Avg| 39ms| 29ms | -10ms | -25.965
| |  P99| 435ms| 287ms | -148ms | -34.034
| ChannelStore.GetAllChannelMembersForUser |  Avg| 20ms| 17ms | -3ms | -14.999
| |  P99| 225ms| 201ms | -24ms | -10.683
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 35ms| 30ms | -5ms | -14.416
| |  P99| 430ms| 378ms | -52ms | -12.106
| ChannelStore.GetByName |  Avg| 15ms| 13ms | -2ms | -13.387
| |  P99| 214ms| 177ms | -37ms | -17.324
| ChannelStore.GetByNameIncludeDeleted |  Avg| 42ms| 0s | -42ms | -98.877
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.GetChannelUnread |  Avg| 23ms| 18ms | -5ms | -21.410
| |  P99| 250ms| 223ms | -27ms | -10.813
| ChannelStore.GetChannels |  Avg| 23ms| 18ms | -5ms | -22.003
| |  P99| 248ms| 224ms | -24ms | -9.681
| ChannelStore.GetChannelsByUser |  Avg| 25ms| 19ms | -6ms | -24.053
| |  P99| 248ms| 226ms | -22ms | -8.853
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 17ms| 13ms | -4ms | -23.243
| |  P99| 231ms| 196ms | -35ms | -15.130
| ChannelStore.GetFileCount |  Avg| 18ms| 16ms | -2ms | -10.981
| |  P99| 226ms| 198ms | -28ms | -12.376
| ChannelStore.GetGuestCount |  Avg| 17ms| 13ms | -4ms | -23.338
| |  P99| 231ms| 193ms | -38ms | -16.421
| ChannelStore.GetMember |  Avg| 17ms| 15ms | -2ms | -11.679
| |  P99| 200ms| 183ms | -17ms | -8.481
| ChannelStore.GetMemberCount |  Avg| 41ms| 37ms | -4ms | -9.698
| |  P99| 250ms| 236ms | -14ms | -5.609
| ChannelStore.GetMemberCountsByGroup |  Avg| 39ms| 0s | -39ms | -99.734
| |  P99| 230ms| 0s | -230ms | -99.784
| ChannelStore.GetMemberForPost |  Avg| 29ms| 23ms | -6ms | -20.873
| |  P99| 326ms| 236ms | -90ms | -27.603
| ChannelStore.GetMemberLastViewedAt |  Avg| 11ms| 9ms | -2ms | -17.446
| |  P99| 196ms| 145ms | -51ms | -25.987
| ChannelStore.GetMembers |  Avg| 57ms| 2ms | -55ms | -96.532
| |  P99| 243ms| 5ms | -238ms | -98.144
| ChannelStore.GetMembersForUser |  Avg| 23ms| 18ms | -5ms | -22.007
| |  P99| 248ms| 223ms | -25ms | -10.089
| ChannelStore.GetMembersForUserWithPagination |  Avg| 28ms| 47ms | 19ms | 68.198
| |  P99| 97ms| 235ms | 138ms | 142.267
| ChannelStore.GetPinnedPostCount |  Avg| 19ms| 14ms | -5ms | -26.372
| |  P99| 242ms| 204ms | -38ms | -15.686
| ChannelStore.GetPublicChannelsForTeam |  Avg| 39ms| 29ms | -10ms | -25.548
| |  P99| 371ms| 211ms | -160ms | -43.109
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 42ms| 35ms | -7ms | -16.482
| |  P99| 474ms| 365ms | -109ms | -22.972
| ChannelStore.GetSidebarCategory |  Avg| 56ms| 34ms | -22ms | -39.412
| |  P99| 456ms| 360ms | -96ms | -21.057
| ChannelStore.GetTeamChannels |  Avg| 50ms| 49ms | -1ms | -2.014
| |  P99| 422ms| 422ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 14ms| 13ms | -1ms | -6.917
| |  P99| 180ms| 158ms | -22ms | -12.230
| ChannelStore.IsReadOnlyChannel |  Avg| 19ms| 15ms | -4ms | -21.318
| |  P99| 235ms| 208ms | -27ms | -11.513
| ChannelStore.Save |  Avg| 81ms| 56ms | -25ms | -30.958
| |  P99| 723ms| 444ms | -279ms | -38.573
| ChannelStore.SaveMember |  Avg| 90ms| 77ms | -13ms | -14.430
| |  P99| 920ms| 746ms | -174ms | -18.922
| ChannelStore.SearchGroupChannels |  Avg| 27ms| 21ms | -6ms | -22.499
| |  P99| 316ms| 227ms | -89ms | -28.126
| ChannelStore.UpdateLastViewedAt |  Avg| 16ms| 15ms | -1ms | -6.275
| |  P99| 163ms| 137ms | -26ms | -15.903
| ChannelStore.UpdateSidebarCategories |  Avg| 218ms| 147ms | -71ms | -32.638
| |  P99| 2.005s| 1.195s | -810ms | -40.400
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 14ms| 13ms | -1ms | -6.969
| |  P99| 174ms| 158ms | -16ms | -9.211
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 243ms| 228ms | -15ms | -6.179
| CommandWebhookStore.Cleanup |  Avg| 7ms| 45ms | 38ms | 580.578
| |  P99| 25ms| 244ms | 219ms | 892.053
| DraftStore.Delete |  Avg| 19ms| 18ms | -1ms | -5.332
| |  P99| 196ms| 191ms | -5ms | -2.547
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 21ms| 19ms | -2ms | -9.646
| |  P99| 94ms| 86ms | -8ms | -8.496
| DraftStore.Get |  Avg| 27ms| 21ms | -6ms | -22.305
| |  P99| 320ms| 236ms | -84ms | -26.286
| DraftStore.GetDraftsForUser |  Avg| 25ms| 22ms | -3ms | -11.842
| |  P99| 247ms| 236ms | -11ms | -4.460
| DraftStore.Upsert |  Avg| 21ms| 19ms | -2ms | -9.428
| |  P99| 211ms| 201ms | -10ms | -4.743
| EmojiStore.GetByName |  Avg| 18ms| 13ms | -5ms | -28.212
| |  P99| 235ms| 186ms | -49ms | -20.848
| EmojiStore.GetMultipleByName |  Avg| 44ms| 30ms | -14ms | -31.928
| |  P99| 244ms| 96ms | -148ms | -60.656
| EmojiStore.Search |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 30ms| 28ms | -2ms | -6.650
| |  P99| 239ms| 250ms | 11ms | 4.600
| FileInfoStore.Get |  Avg| 20ms| 17ms | -3ms | -14.798
| |  P99| 241ms| 218ms | -23ms | -9.560
| FileInfoStore.GetByIds |  Avg| 21ms| 18ms | -3ms | -14.136
| |  P99| 318ms| 228ms | -90ms | -28.293
| FileInfoStore.GetForPost |  Avg| 23ms| 15ms | -8ms | -35.227
| |  P99| 290ms| 214ms | -76ms | -26.194
| FileInfoStore.Save |  Avg| 23ms| 20ms | -3ms | -13.232
| |  P99| 218ms| 196ms | -22ms | -10.094
| FileInfoStore.SetContent |  Avg| 35ms| 26ms | -9ms | -25.514
| |  P99| 363ms| 224ms | -139ms | -38.324
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 11ms| 8ms | -3ms | -28.158
| |  P99| 190ms| 132ms | -58ms | -30.490
| GroupStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 180ms| 154ms | -26ms | -14.430
| GroupStore.GetGroups |  Avg| 18ms| 14ms | -4ms | -22.190
| |  P99| 237ms| 197ms | -40ms | -16.875
| JobStore.GetAllByStatus |  Avg| 23ms| 19ms | -4ms | -17.681
| |  P99| 274ms| 237ms | -37ms | -13.486
| JobStore.GetAllByTypePage |  Avg| 34ms| 22ms | -12ms | -35.336
| |  P99| 221ms| 206ms | -15ms | -6.772
| JobStore.GetCountByStatusAndType |  Avg| 39ms| 18ms | -21ms | -54.140
| |  P99| 713ms| 263ms | -450ms | -63.158
| JobStore.GetNewestJobByStatusesAndType |  Avg| 29ms| 13ms | -16ms | -55.274
| |  P99| 478ms| 216ms | -262ms | -54.869
| JobStore.Save |  Avg| 26ms| 16ms | -10ms | -38.368
| |  P99| 250ms| 180ms | -70ms | -28.000
| JobStore.UpdateOptimistically |  Avg| 10ms| 19ms | 9ms | 92.615
| |  P99| 83ms| 230ms | 147ms | 177.118
| JobStore.UpdateStatus |  Avg| 11ms| 13ms | 2ms | 18.357
| |  P99| 83ms| 111ms | 28ms | 33.535
| JobStore.UpdateStatusOptimistically |  Avg| 13ms| 12ms | -1ms | -7.989
| |  P99| 90ms| 88ms | -2ms | -2.225
| LicenseStore.GetAll |  Avg| 1ms| 12ms | 11ms | 1550.904
| |  P99| 5ms| 49ms | 44ms | 888.524
| LinkMetadataStore.Get |  Avg| 18ms| 13ms | -5ms | -28.039
| |  P99| 241ms| 201ms | -40ms | -16.623
| LinkMetadataStore.Save |  Avg| 13ms| 10ms | -3ms | -23.277
| |  P99| 87ms| 74ms | -13ms | -14.943
| PluginStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 92ms | -5ms | -5.143
| PluginStore.Get |  Avg| 19ms| 33ms | 14ms | 72.384
| |  P99| 95ms| 232ms | 137ms | 143.455
| PluginStore.List |  Avg| 16ms| 18ms | 2ms | 12.255
| |  P99| 221ms| 215ms | -6ms | -2.709
| PluginStore.SetWithOptions |  Avg| 20ms| 18ms | -2ms | -10.119
| |  P99| 218ms| 202ms | -16ms | -7.352
| PostAcknowledgementStore.GetForPost |  Avg| 12ms| 10ms | -2ms | -16.523
| |  P99| 168ms| 171ms | 3ms | 1.783
| PostAcknowledgementStore.GetForPosts |  Avg| 27ms| 20ms | -7ms | -26.068
| |  P99| 449ms| 312ms | -137ms | -30.481
| PostPersistentNotificationStore.DeleteExpired |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 158ms| 166ms | 8ms | 5.048
| PostPersistentNotificationStore.Get |  Avg| 8ms| 15ms | 7ms | 84.849
| |  P99| 69ms| 360ms | 291ms | 418.751
| PostPersistentNotificationStore.GetSingle |  Avg| 15ms| 11ms | -4ms | -26.329
| |  P99| 230ms| 184ms | -46ms | -20.003
| PostPriorityStore.GetForPost |  Avg| 13ms| 11ms | -2ms | -15.023
| |  P99| 220ms| 200ms | -20ms | -9.080
| PostPriorityStore.GetForPosts |  Avg| 28ms| 21ms | -7ms | -25.018
| |  P99| 454ms| 314ms | -140ms | -30.857
| PostStore.AnalyticsPostCount |  Avg| 202ms| 256ms | 54ms | 26.750
| |  P99| 496ms| 496ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 18ms | 17ms | 2076.668
| |  P99| 5ms| 49ms | 44ms | 888.524
| PostStore.Delete |  Avg| 119ms| 75ms | -44ms | -36.953
| |  P99| 912ms| 430ms | -482ms | -52.822
| PostStore.Get |  Avg| 46ms| 35ms | -11ms | -23.992
| |  P99| 476ms| 369ms | -107ms | -22.480
| PostStore.GetEtag |  Avg| 21ms| 17ms | -4ms | -18.732
| |  P99| 245ms| 222ms | -23ms | -9.396
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 10ms| 9ms | -1ms | -10.330
| |  P99| 100ms| 94ms | -6ms | -6.009
| PostStore.GetPostIdBeforeTime |  Avg| 15ms| 13ms | -2ms | -13.409
| |  P99| 177ms| 158ms | -19ms | -10.761
| PostStore.GetPostReminderMetadata |  Avg| 27ms| 20ms | -7ms | -25.891
| |  P99| 247ms| 246ms | -1ms | -0.405
| PostStore.GetPostReminders |  Avg| 35ms| 46ms | 11ms | 31.149
| |  P99| 231ms| 415ms | 184ms | 79.482
| PostStore.GetPosts |  Avg| 11ms| 9ms | -2ms | -17.821
| |  P99| 178ms| 129ms | -49ms | -27.564
| PostStore.GetPostsAfter |  Avg| 20ms| 14ms | -6ms | -29.873
| |  P99| 239ms| 191ms | -48ms | -20.048
| PostStore.GetPostsBefore |  Avg| 23ms| 19ms | -4ms | -17.129
| |  P99| 246ms| 224ms | -22ms | -8.952
| PostStore.GetPostsByThread |  Avg| 24ms| 20ms | -4ms | -16.835
| |  P99| 239ms| 204ms | -35ms | -14.620
| PostStore.GetPostsSince |  Avg| 38ms| 32ms | -6ms | -15.970
| |  P99| 320ms| 240ms | -80ms | -24.974
| PostStore.GetSingle |  Avg| 17ms| 13ms | -4ms | -23.167
| |  P99| 239ms| 196ms | -43ms | -17.989
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 59ms| 53ms | -6ms | -10.087
| |  P99| 484ms| 454ms | -30ms | -6.197
| PostStore.SearchPostsForUser |  Avg| 77ms| 61ms | -16ms | -20.783
| |  P99| 2.071s| 1.269s | -802ms | -38.727
| PostStore.SetPostReminder |  Avg| 51ms| 41ms | -10ms | -19.758
| |  P99| 435ms| 233ms | -202ms | -46.437
| PostStore.Update |  Avg| 44ms| 44ms | 0s | 0.000
| |  P99| 270ms| 248ms | -22ms | -8.149
| PreferenceStore.DeleteCategoryAndName |  Avg| 22ms| 15ms | -7ms | -31.359
| |  P99| 412ms| 208ms | -204ms | -49.455
| PreferenceStore.Get |  Avg| 19ms| 15ms | -4ms | -20.606
| |  P99| 240ms| 211ms | -29ms | -12.075
| PreferenceStore.GetAll |  Avg| 18ms| 14ms | -4ms | -21.840
| |  P99| 233ms| 201ms | -32ms | -13.751
| PreferenceStore.Save |  Avg| 42ms| 39ms | -3ms | -7.094
| |  P99| 397ms| 360ms | -37ms | -9.329
| ProductNoticesStore.ClearOldNotices |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 66ms| 87ms | 21ms | 31.970
| |  P99| 100ms| 100ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 112ms| 109ms | -3ms | -2.669
| |  P99| 911ms| 890ms | -21ms | -2.306
| ReactionStore.GetForPost |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 198ms| 206ms | 8ms | 4.032
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -104.009
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 14ms| 26ms | 12ms | 82.830
| |  P99| 90ms| 121ms | 31ms | 34.254
| RoleStore.GetByNames |  Avg| 38ms| 53ms | 15ms | 39.342
| |  P99| 236ms| 245ms | 9ms | 3.810
| ScheduledPostStore.CreateScheduledPost |  Avg| 19ms| 25ms | 6ms | 31.368
| |  P99| 173ms| 220ms | 47ms | 27.090
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 41ms| 25ms | -16ms | -39.282
| |  P99| 454ms| 224ms | -230ms | -50.689
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 13ms| 10ms | -3ms | -23.841
| |  P99| 206ms| 161ms | -45ms | -21.807
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 18ms| 14ms | -4ms | -22.188
| |  P99| 195ms| 83ms | -112ms | -57.584
| SchemeStore.GetAllPage |  Avg| 7ms| 3ms | -4ms | -58.291
| |  P99| 10ms| 5ms | -5ms | -50.251
| SessionStore.Get |  Avg| 26ms| 23ms | -3ms | -11.670
| |  P99| 274ms| 240ms | -34ms | -12.398
| SessionStore.GetLRUSessions |  Avg| 10ms| 8ms | -2ms | -20.990
| |  P99| 164ms| 122ms | -42ms | -25.630
| SessionStore.GetSessionsExpired |  Avg| 7ms| 21ms | 14ms | 199.569
| |  P99| 48ms| 229ms | 181ms | 376.108
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 15ms| 11ms | -4ms | -26.560
| |  P99| 233ms| 196ms | -37ms | -15.854
| SessionStore.Remove |  Avg| 14ms| 19ms | 5ms | 35.361
| |  P99| 88ms| 225ms | 137ms | 155.683
| SessionStore.Save |  Avg| 21ms| 19ms | -2ms | -9.587
| |  P99| 234ms| 220ms | -14ms | -5.994
| SessionStore.UpdateLastActivityAt |  Avg| 16ms| 14ms | -2ms | -12.806
| |  P99| 167ms| 140ms | -27ms | -16.174
| SharedChannelStore.HasChannel |  Avg| 16ms| 13ms | -3ms | -19.185
| |  P99| 221ms| 188ms | -33ms | -14.917
| StatusStore.Get |  Avg| 16ms| 13ms | -3ms | -18.479
| |  P99| 232ms| 200ms | -32ms | -13.816
| StatusStore.GetByIds |  Avg| 29ms| 24ms | -5ms | -17.065
| |  P99| 343ms| 242ms | -101ms | -29.467
| StatusStore.SaveOrUpdate |  Avg| 43ms| 27ms | -16ms | -37.090
| |  P99| 669ms| 335ms | -334ms | -49.905
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 25ms| 23ms | -2ms | -8.163
| |  P99| 408ms| 217ms | -191ms | -46.871
| StatusStore.UpdateLastActivityAt |  Avg| 16ms| 14ms | -2ms | -12.892
| |  P99| 170ms| 142ms | -28ms | -16.490
| SystemStore.GetByName |  Avg| 12ms| 11ms | -1ms | -8.377
| |  P99| 161ms| 129ms | -32ms | -19.924
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 19ms | 18ms | 3040.541
| |  P99| 5ms| 49ms | 44ms | 888.524
| TeamStore.Get |  Avg| 16ms| 12ms | -4ms | -24.510
| |  P99| 236ms| 189ms | -47ms | -19.915
| TeamStore.GetActiveMemberCount |  Avg| 97ms| 68ms | -29ms | -29.859
| |  P99| 422ms| 235ms | -187ms | -44.261
| TeamStore.GetAllPage |  Avg| 14ms| 11ms | -3ms | -21.167
| |  P99| 221ms| 184ms | -37ms | -16.716
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 16ms| 13ms | -3ms | -18.766
| |  P99| 227ms| 194ms | -33ms | -14.544
| TeamStore.GetMember |  Avg| 11ms| 10ms | -1ms | -8.785
| |  P99| 165ms| 112ms | -53ms | -32.083
| TeamStore.GetTeamsByUserId |  Avg| 15ms| 12ms | -3ms | -19.584
| |  P99| 225ms| 190ms | -35ms | -15.560
| TeamStore.GetTeamsForUser |  Avg| 14ms| 12ms | -2ms | -14.331
| |  P99| 212ms| 181ms | -31ms | -14.599
| TeamStore.GetTotalMemberCount |  Avg| 85ms| 61ms | -24ms | -28.119
| |  P99| 461ms| 227ms | -234ms | -50.732
| TeamStore.SaveMember |  Avg| 58ms| 54ms | -4ms | -6.915
| |  P99| 458ms| 400ms | -58ms | -12.655
| ThreadStore.Get |  Avg| 23ms| 17ms | -6ms | -25.767
| |  P99| 230ms| 321ms | 91ms | 39.591
| ThreadStore.GetMembershipForUser |  Avg| 19ms| 15ms | -4ms | -20.913
| |  P99| 245ms| 211ms | -34ms | -13.904
| ThreadStore.GetTeamsUnreadForUser |  Avg| 24ms| 18ms | -6ms | -25.332
| |  P99| 344ms| 238ms | -106ms | -30.834
| ThreadStore.GetThreadFollowers |  Avg| 16ms| 13ms | -3ms | -18.191
| |  P99| 238ms| 198ms | -40ms | -16.812
| ThreadStore.GetThreadForUser |  Avg| 31ms| 25ms | -6ms | -19.335
| |  P99| 407ms| 274ms | -133ms | -32.651
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 27ms| 23ms | -4ms | -14.952
| |  P99| 241ms| 217ms | -24ms | -9.967
| ThreadStore.GetThreadsForUser |  Avg| 26ms| 20ms | -6ms | -23.086
| |  P99| 286ms| 228ms | -58ms | -20.291
| ThreadStore.GetTotalThreads |  Avg| 16ms| 12ms | -4ms | -25.420
| |  P99| 226ms| 190ms | -36ms | -15.904
| ThreadStore.GetTotalUnreadMentions |  Avg| 16ms| 13ms | -3ms | -18.351
| |  P99| 233ms| 193ms | -40ms | -17.190
| ThreadStore.GetTotalUnreadThreads |  Avg| 15ms| 13ms | -2ms | -12.924
| |  P99| 226ms| 193ms | -33ms | -14.585
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 16ms| 13ms | -3ms | -18.745
| |  P99| 224ms| 194ms | -30ms | -13.411
| ThreadStore.MaintainMembership |  Avg| 35ms| 31ms | -4ms | -11.475
| |  P99| 343ms| 274ms | -69ms | -20.144
| ThreadStore.MarkAllAsReadByChannels |  Avg| 17ms| 14ms | -3ms | -18.143
| |  P99| 186ms| 161ms | -25ms | -13.418
| ThreadStore.MarkAllAsReadByTeam |  Avg| 34ms| 39ms | 5ms | 14.809
| |  P99| 98ms| 236ms | 138ms | 140.816
| ThreadStore.MarkAsRead |  Avg| 15ms| 14ms | -1ms | -6.493
| |  P99| 158ms| 125ms | -33ms | -20.932
| ThreadStore.UpdateMembership |  Avg| 15ms| 13ms | -2ms | -13.351
| |  P99| 153ms| 121ms | -32ms | -20.854
| TokenStore.Cleanup |  Avg| 5ms| 45ms | 40ms | 880.305
| |  P99| 10ms| 244ms | 234ms | 2375.633
| UserAccessTokenStore.GetByToken |  Avg| 24ms| 14ms | -10ms | -41.464
| |  P99| 223ms| 212ms | -11ms | -4.922
| UserStore.AnalyticsActiveCount |  Avg| 27ms| 68ms | 41ms | 153.884
| |  P99| 50ms| 245ms | 195ms | 393.938
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 72ms | 71ms | 7971.697
| |  P99| 5ms| 245ms | 240ms | 4846.493
| UserStore.AutocompleteUsersInChannel |  Avg| 88ms| 81ms | -7ms | -7.989
| |  P99| 475ms| 433ms | -42ms | -8.849
| UserStore.Count |  Avg| 26ms| 41ms | 15ms | 57.718
| |  P99| 228ms| 238ms | 10ms | 4.381
| UserStore.Get |  Avg| 17ms| 14ms | -3ms | -17.694
| |  P99| 225ms| 194ms | -31ms | -13.759
| UserStore.GetAllProfiles |  Avg| 12ms| 10ms | -2ms | -17.082
| |  P99| 190ms| 134ms | -56ms | -29.444
| UserStore.GetAllProfilesInChannel |  Avg| 434ms| 397ms | -37ms | -8.521
| |  P99| 2.328s| 2.248s | -80ms | -3.436
| UserStore.GetByUsername |  Avg| 30ms| 18ms | -12ms | -40.164
| |  P99| 410ms| 216ms | -194ms | -47.281
| UserStore.GetForLogin |  Avg| 11ms| 10ms | -1ms | -8.766
| |  P99| 189ms| 160ms | -29ms | -15.311
| UserStore.GetMany |  Avg| 21ms| 13ms | -8ms | -37.998
| |  P99| 249ms| 185ms | -64ms | -25.652
| UserStore.GetProfileByIds |  Avg| 23ms| 18ms | -5ms | -21.777
| |  P99| 246ms| 222ms | -24ms | -9.756
| UserStore.GetProfilesByUsernames |  Avg| 22ms| 18ms | -4ms | -18.311
| |  P99| 242ms| 222ms | -20ms | -8.276
| UserStore.GetProfilesInChannel |  Avg| 28ms| 14ms | -14ms | -50.431
| |  P99| 234ms| 92ms | -142ms | -60.716
| UserStore.GetProfilesNotInChannel |  Avg| 14ms| 17ms | 3ms | 21.745
| |  P99| 92ms| 96ms | 4ms | 4.336
| UserStore.GetUnreadCount |  Avg| 17ms| 13ms | -4ms | -24.027
| |  P99| 235ms| 197ms | -38ms | -16.168
| UserStore.IsEmpty |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 85ms| 74ms | -11ms | -12.925
| UserStore.Save |  Avg| 101ms| 102ms | 1ms | 0.992
| |  P99| 460ms| 463ms | 3ms | 0.653
| UserStore.Search |  Avg| 59ms| 53ms | -6ms | -10.183
| |  P99| 355ms| 247ms | -108ms | -30.419
| UserStore.Update |  Avg| 41ms| 38ms | -3ms | -7.233
| |  P99| 359ms| 305ms | -54ms | -15.042
| UserStore.UpdateFailedPasswordAttempts |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 144ms| 128ms | -16ms | -11.144
| UserStore.UpdateLastLogin |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.024
| UserStore.UpdateUpdateAt |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 98ms| 95ms | -3ms | -3.069
| UserTermsOfServiceStore.GetByUser |  Avg| 13ms| 10ms | -3ms | -23.797
| |  P99| 208ms| 169ms | -39ms | -18.759
| WebhookStore.GetOutgoingByTeam |  Avg| 24ms| 19ms | -5ms | -21.140
| |  P99| 248ms| 227ms | -21ms | -8.452
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 698ms| 621ms | -77ms | -11.038
| | P99| 4.253s| 4.059s | -194ms | -4.562
| addTeamMember | Avg| 1.703s| 1.537s | -166ms | -9.750
| | P99| 10s| 9.483s | -517ms | -5.170
| autocompleteChannelsForTeamForSearch | Avg| 120ms| 79ms | -41ms | -34.255
| | P99| 1.727s| 541ms | -1.186s | -68.655
| autocompleteEmojis | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 84ms| 76ms | -8ms | -9.545
| | P99| 491ms| 445ms | -46ms | -9.366
| channelMemberCountsByGroup | Avg| 55ms| 0s | -55ms | -99.556
| | P99| 243ms| 0s | -243ms | -99.795
| createCategoryForTeamForUser | Avg| 89ms| 90ms | 1ms | 1.123
| | P99| 242ms| 478ms | 236ms | 97.320
| createChannel | Avg| 943ms| 818ms | -125ms | -13.255
| | P99| 4.225s| 4.612s | 387ms | 9.160
| createChannelBookmark | Avg| 100ms| 61ms | -39ms | -38.885
| | P99| 855ms| 242ms | -613ms | -71.697
| createDirectChannel | Avg| 718ms| 592ms | -126ms | -17.540
| | P99| 3.3s| 2.462s | -838ms | -25.395
| createEmoji | Avg| 5ms| 0s | -5ms | -92.247
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 1.216s| 925ms | -291ms | -23.922
| | P99| 8.339s| 4.391s | -3.948s | -47.345
| createPost | Avg| 976ms| 855ms | -121ms | -12.398
| | P99| 7.026s| 4.864s | -2.162s | -30.771
| createSchedulePost | Avg| 26ms| 35ms | 9ms | 35.042
| | P99| 249ms| 500ms | 251ms | 100.643
| createUser | Avg| 326ms| 313ms | -13ms | -3.984
| | P99| 2.295s| 2.231s | -64ms | -2.788
| deleteChannelBookmark | Avg| 246ms| 245ms | -1ms | -0.407
| | P99| 980ms| 249ms | -731ms | -74.592
| deleteDraft | Avg| 28ms| 22ms | -6ms | -21.306
| | P99| 340ms| 240ms | -100ms | -29.439
| deletePost | Avg| 193ms| 127ms | -66ms | -34.143
| | P99| 1.975s| 860ms | -1.115s | -56.457
| followThreadByUser | Avg| 103ms| 107ms | 4ms | 3.880
| | P99| 480ms| 765ms | 285ms | 59.324
| getAllTeams | Avg| 17ms| 14ms | -3ms | -17.887
| | P99| 239ms| 211ms | -28ms | -11.723
| getCategoriesForTeamForUser | Avg| 43ms| 36ms | -7ms | -16.194
| | P99| 478ms| 378ms | -100ms | -20.929
| getChannel | Avg| 50ms| 35ms | -15ms | -29.882
| | P99| 689ms| 406ms | -283ms | -41.067
| getChannelMember | Avg| 39ms| 33ms | -6ms | -15.382
| | P99| 454ms| 382ms | -72ms | -15.847
| getChannelMembers | Avg| 58ms| 2ms | -56ms | -97.118
| | P99| 243ms| 5ms | -238ms | -98.144
| getChannelMembersForTeamForUser | Avg| 23ms| 19ms | -4ms | -17.111
| | P99| 251ms| 226ms | -25ms | -9.966
| getChannelStats | Avg| 10ms| 9ms | -1ms | -10.149
| | P99| 210ms| 191ms | -19ms | -9.049
| getChannelUnread | Avg| 26ms| 20ms | -6ms | -22.935
| | P99| 316ms| 234ms | -82ms | -25.927
| getChannelsForTeamForUser | Avg| 23ms| 19ms | -4ms | -17.026
| | P99| 252ms| 228ms | -24ms | -9.542
| getChannelsForUser | Avg| 25ms| 19ms | -6ms | -23.613
| | P99| 267ms| 228ms | -39ms | -14.615
| getClientConfig | Avg| 36ms| 32ms | -4ms | -11.097
| | P99| 381ms| 340ms | -41ms | -10.761
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 27ms| 24ms | -3ms | -11.005
| | P99| 296ms| 250ms | -46ms | -15.561
| getFilePreview | Avg| 85ms| 81ms | -4ms | -4.688
| | P99| 492ms| 472ms | -20ms | -4.069
| getFileThumbnail | Avg| 75ms| 69ms | -6ms | -7.994
| | P99| 481ms| 446ms | -35ms | -7.269
| getFilteredUsersStats | Avg| 29ms| 135ms | 106ms | 365.652
| | P99| 50ms| 247ms | 197ms | 395.980
| getJobsByType | Avg| 34ms| 21ms | -13ms | -37.881
| | P99| 221ms| 207ms | -14ms | -6.321
| getPostThread | Avg| 114ms| 82ms | -32ms | -28.182
| | P99| 1.574s| 871ms | -703ms | -44.656
| getPostsForChannel | Avg| 211ms| 157ms | -54ms | -25.579
| | P99| 3.268s| 2.197s | -1.071s | -32.772
| getPostsForChannelAroundLastUnread | Avg| 76ms| 62ms | -14ms | -18.543
| | P99| 952ms| 730ms | -222ms | -23.309
| getPreferences | Avg| 19ms| 14ms | -5ms | -25.739
| | P99| 241ms| 210ms | -31ms | -12.873
| getPrevTrialLicense | Avg| 1ms| 36ms | 35ms | 6772.171
| | P99| 5ms| 50ms | 45ms | 908.719
| getProfileImage | Avg| 72ms| 69ms | -3ms | -4.154
| | P99| 479ms| 471ms | -8ms | -1.670
| getPublicChannelsForTeam | Avg| 41ms| 30ms | -11ms | -27.143
| | P99| 371ms| 213ms | -158ms | -42.570
| getRolesByNames | Avg| 2ms| 4ms | 2ms | 96.251
| | P99| 5ms| 47ms | 42ms | 848.485
| getTeamMember | Avg| 21ms| 18ms | -3ms | -14.252
| | P99| 223ms| 205ms | -18ms | -8.080
| getTeamMembersForUser | Avg| 17ms| 15ms | -2ms | -11.438
| | P99| 235ms| 221ms | -14ms | -5.948
| getTeamScheduledPosts | Avg| 26ms| 20ms | -6ms | -23.491
| | P99| 371ms| 246ms | -125ms | -33.658
| getTeamStats | Avg| 109ms| 74ms | -35ms | -32.130
| | P99| 474ms| 241ms | -233ms | -49.139
| getTeamsForUser | Avg| 16ms| 12ms | -4ms | -25.568
| | P99| 228ms| 193ms | -35ms | -15.360
| getTeamsUnreadForUser | Avg| 30ms| 23ms | -7ms | -23.245
| | P99| 433ms| 312ms | -121ms | -27.943
| getThreadsForUser | Avg| 27ms| 21ms | -6ms | -22.072
| | P99| 335ms| 236ms | -99ms | -29.593
| getUser | Avg| 32ms| 24ms | -8ms | -24.836
| | P99| 451ms| 356ms | -95ms | -21.075
| getUserByUsername | Avg| 61ms| 73ms | 12ms | 19.809
| | P99| 100ms| 247ms | 147ms | 147.709
| getUserStatus | Avg| 1ms| 0s | -1ms | -187.886
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 6ms| 5ms | -1ms | -15.472
| | P99| 179ms| 144ms | -35ms | -19.594
| getUsers | Avg| 28ms| 22ms | -6ms | -21.240
| | P99| 421ms| 343ms | -78ms | -18.532
| getUsersByIds | Avg| 5ms| 4ms | -1ms | -21.990
| | P99| 86ms| 74ms | -12ms | -13.911
| getUsersByNames | Avg| 23ms| 19ms | -4ms | -17.663
| | P99| 245ms| 226ms | -19ms | -7.765
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 18ms| 15ms | -3ms | -17.104
| | P99| 236ms| 215ms | -21ms | -8.901
| login | Avg| 152ms| 144ms | -8ms | -5.258
| | P99| 1.56s| 1.32s | -240ms | -15.385
| logout | Avg| 228ms| 199ms | -29ms | -12.725
| | P99| 970ms| 2.132s | 1.162s | 119.794
| patchPost | Avg| 151ms| 129ms | -22ms | -14.523
| | P99| 1.911s| 986ms | -925ms | -48.413
| removeUserCustomStatus | Avg| 452ms| 368ms | -84ms | -18.597
| | P99| 2.357s| 2.182s | -175ms | -7.424
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 66ms| 53ms | -13ms | -19.804
| | P99| 800ms| 486ms | -314ms | -39.241
| searchAllChannels | Avg| 63ms| 57ms | -6ms | -9.599
| | P99| 365ms| 308ms | -57ms | -15.601
| searchGroupChannels | Avg| 27ms| 21ms | -6ms | -22.097
| | P99| 331ms| 229ms | -102ms | -30.780
| searchPostsInTeam | Avg| 118ms| 97ms | -21ms | -17.731
| | P99| 2.432s| 1.94s | -492ms | -20.228
| searchUsers | Avg| 61ms| 55ms | -6ms | -9.840
| | P99| 369ms| 248ms | -121ms | -32.759
| setPostReminder | Avg| 149ms| 95ms | -54ms | -36.139
| | P99| 1.72s| 480ms | -1.24s | -72.095
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 98ms| 79ms | -19ms | -19.460
| | P99| 925ms| 827ms | -98ms | -10.595
| updateCategoriesForTeamForUser | Avg| 349ms| 224ms | -125ms | -35.808
| | P99| 2.377s| 2.07s | -307ms | -12.913
| updateChannelBookmark | Avg| 203ms| 122ms | -81ms | -39.852
| | P99| 960ms| 248ms | -712ms | -74.167
| updateChannelBookmarkSortOrder | Avg| 86ms| 80ms | -6ms | -7.011
| | P99| 246ms| 247ms | 1ms | 0.406
| updatePreferences | Avg| 66ms| 58ms | -8ms | -12.142
| | P99| 471ms| 461ms | -10ms | -2.122
| updateReadStateAllThreadsByUser | Avg| 34ms| 60ms | 26ms | 76.735
| | P99| 98ms| 477ms | 379ms | 386.735
| updateReadStateThreadByUser | Avg| 217ms| 177ms | -40ms | -18.443
| | P99| 2.182s| 1.725s | -457ms | -20.943
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 269.703
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 585ms| 578ms | -7ms | -1.197
| | P99| 2.356s| 2.349s | -7ms | -0.297
| upsertDraft | Avg| 28ms| 25ms | -3ms | -10.537
| | P99| 248ms| 237ms | -11ms | -4.442
| viewChannel | Avg| 98ms| 78ms | -20ms | -20.340
| | P99| 988ms| 818ms | -170ms | -17.215
