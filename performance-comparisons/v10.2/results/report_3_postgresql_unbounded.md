### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 1ms | 16ms | 15ms | 2381.73
| CommandWebhookStore.Cleanup | avg | 1ms | 12ms | 11ms | 1464.13
| UserStore.GetProfilesInChannel | avg | 5ms | 56ms | 51ms | 972.87
| LicenseStore.GetAll | avg | 2ms | 9ms | 7ms | 354.66
| RetentionPolicyStore.GetAll | avg | 6ms | 26ms | 20ms | 353.50
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 6ms | 26ms | 20ms | 334.79
| UserStore.AnalyticsGetInactiveUsersCount | avg | 4ms | 11ms | 7ms | 163.61
| RetentionPolicyStore.GetCount | avg | 9ms | 24ms | 15ms | 160.21
| PostStore.AnalyticsPostCount | avg | 306ms | 679ms | 373ms | 121.80
| UserAccessTokenStore.GetByToken | avg | 5ms | 9ms | 4ms | 76.09
| JobStore.GetAllByTypePage | avg | 15ms | 26ms | 11ms | 75.61
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 7ms | 11ms | 4ms | 59.34
| SessionStore.Remove | avg | 5ms | 8ms | 3ms | 59.00
| JobStore.GetNewestJobByStatusesAndType | avg | 6ms | 9ms | 3ms | 51.06
| PostStore.SetPostReminder | avg | 16ms | 24ms | 8ms | 49.73
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 6ms | 2ms | 45.28
| PostStore.GetPostReminders | avg | 9ms | 13ms | 4ms | 45.04
| LinkMetadataStore.Save | avg | 5ms | 7ms | 2ms | 37.48
| ChannelStore.GetSidebarCategory | avg | 29ms | 40ms | 11ms | 37.48
| PostPersistentNotificationStore.Get | avg | 6ms | 8ms | 2ms | 35.47
| RoleStore.GetByNames | avg | 13ms | 17ms | 4ms | 29.66
| ChannelStore.Get | avg | 15ms | 19ms | 4ms | 26.68
| JobStore.Save | avg | 8ms | 10ms | 2ms | 25.10
| ChannelStore.GetByName | avg | 8ms | 10ms | 2ms | 23.58
| JobStore.GetCountByStatusAndType | avg | 10ms | 12ms | 2ms | 20.36
| DraftStore.GetDraftsForUser | avg | 11ms | 13ms | 2ms | 17.56
| StatusStore.GetByIds | avg | 12ms | 14ms | 2ms | 16.53
| ChannelStore.SaveMember | avg | 50ms | 56ms | 6ms | 12.03
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 29ms | 32ms | 3ms | 10.32
| PreferenceStore.Save | avg | 20ms | 22ms | 2ms | 10.16
| ChannelStore.GetPublicChannelsForTeam | avg | 30ms | 33ms | 3ms | 9.91
| PostStore.Get | avg | 20ms | 22ms | 2ms | 9.79
| TeamStore.SaveMember | avg | 40ms | 43ms | 3ms | 7.49
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 28ms | 30ms | 2ms | 7.21
| ChannelStore.Autocomplete | avg | 56ms | 60ms | 4ms | 7.08
| PostStore.Save | avg | 29ms | 31ms | 2ms | 6.83
| ChannelStore.GetMemberCount | avg | 36ms | 38ms | 2ms | 5.60
| UserStore.GetAllProfilesInChannel | avg | 425ms | 445ms | 20ms | 4.71
| UserStore.Search | avg | 54ms | 56ms | 2ms | 3.71
| TeamStore.GetTotalMemberCount | avg | 67ms | 69ms | 2ms | 3.00
| TeamStore.GetActiveMemberCount | avg | 73ms | 75ms | 2ms | 2.73
| UserStore.AutocompleteUsersInChannel | avg | 75ms | 77ms | 2ms | 2.67
| PostStore.SearchPostsForUser | avg | 296ms | 299ms | 3ms | 1.01
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesInChannel | p99 | 24ms | 476ms | 452ms | 1869.61
| TokenStore.Cleanup | p99 | 5ms | 97ms | 92ms | 1858.59
| RetentionPolicyStore.GetAll | p99 | 10ms | 99ms | 89ms | 894.47
| CommandWebhookStore.Cleanup | p99 | 5ms | 48ms | 43ms | 868.49
| RetentionPolicyStore.GetCount | p99 | 10ms | 50ms | 40ms | 402.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 10ms | 50ms | 40ms | 402.01
| PostStore.GetPostReminders | p99 | 47ms | 221ms | 174ms | 366.96
| EmojiStore.GetMultipleByName | p99 | 5ms | 23ms | 18ms | 363.64
| PreferenceStore.DeleteCategoryAndName | p99 | 44ms | 205ms | 161ms | 361.80
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 24ms | 96ms | 72ms | 296.91
| JobStore.GetNewestJobByStatusesAndType | p99 | 48ms | 185ms | 137ms | 284.31
| RoleStore.GetByNames | p99 | 50ms | 155ms | 105ms | 210.76
| JobStore.Save | p99 | 57ms | 170ms | 113ms | 198.25
| PostPersistentNotificationStore.Get | p99 | 74ms | 198ms | 124ms | 168.71
| UserAccessTokenStore.GetByToken | p99 | 47ms | 125ms | 78ms | 164.71
| LicenseStore.GetAll | p99 | 10ms | 25ms | 15ms | 153.85
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 10ms | 25ms | 15ms | 152.28
| PostPersistentNotificationStore.DeleteExpired | p99 | 74ms | 155ms | 81ms | 110.20
| PostStore.AnalyticsPostCount | p99 | 496ms | 993ms | 497ms | 100.15
| ThreadStore.Get | p99 | 100ms | 200ms | 100ms | 100.00
| JobStore.GetCountByStatusAndType | p99 | 101ms | 196ms | 95ms | 93.60
| UserStore.GetProfilesNotInChannel | p99 | 49ms | 95ms | 46ms | 93.28
| BotStore.Get | p99 | 42ms | 81ms | 39ms | 92.86
| ThreadStore.MarkAllAsReadByTeam | p99 | 25ms | 48ms | 23ms | 92.84
| LinkMetadataStore.Save | p99 | 44ms | 80ms | 36ms | 80.90
| PostStore.Delete | p99 | 242ms | 425ms | 183ms | 75.70
| JobStore.GetAllByTypePage | p99 | 124ms | 214ms | 90ms | 72.59
| PostStore.GetEtag | p99 | 107ms | 170ms | 63ms | 58.94
| SessionStore.Remove | p99 | 46ms | 73ms | 27ms | 58.06
| FileInfoStore.GetByIds | p99 | 92ms | 144ms | 52ms | 56.69
| FileInfoStore.GetForPost | p99 | 100ms | 152ms | 52ms | 52.18
| UserStore.GetProfileByIds | p99 | 115ms | 170ms | 55ms | 47.64
| ThreadStore.GetThreadUnreadReplyCount | p99 | 110ms | 161ms | 51ms | 46.48
| PostStore.GetPostReminderMetadata | p99 | 85ms | 124ms | 39ms | 46.02
| ThreadStore.GetMembershipForUser | p99 | 98ms | 142ms | 44ms | 44.80
| ChannelStore.GetPinnedPostCount | p99 | 93ms | 133ms | 40ms | 42.79
| ChannelStore.GetGuestCount | p99 | 95ms | 135ms | 40ms | 42.28
| PostStore.SearchPostsForUser | p99 | 2.974s | 4.23s | 1.256s | 42.24
| TeamStore.SaveMember | p99 | 243ms | 340ms | 97ms | 39.87
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 98ms | 135ms | 37ms | 37.81
| ClusterDiscoveryStore.SetLastPingAt | p99 | 137ms | 188ms | 51ms | 37.23
| JobStore.UpdateOptimistically | p99 | 120ms | 164ms | 44ms | 36.68
| ChannelStore.GetMembersForUser | p99 | 117ms | 159ms | 42ms | 35.90
| FileInfoStore.Save | p99 | 116ms | 157ms | 41ms | 35.21
| PreferenceStore.Get | p99 | 122ms | 165ms | 43ms | 35.20
| PostStore.GetPostsByThread | p99 | 97ms | 129ms | 32ms | 32.98
| UserStore.UpdateUpdateAt | p99 | 61ms | 81ms | 20ms | 32.60
| DraftStore.GetDraftsForUser | p99 | 135ms | 179ms | 44ms | 32.49
| FileInfoStore.Get | p99 | 120ms | 158ms | 38ms | 31.55
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 279ms | 365ms | 86ms | 30.81
| StatusStore.GetByIds | p99 | 153ms | 200ms | 47ms | 30.75
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 69ms | 90ms | 21ms | 30.52
| ChannelStore.GetChannels | p99 | 129ms | 168ms | 39ms | 30.28
| ChannelStore.CreateDirectChannel | p99 | 608ms | 792ms | 184ms | 30.26
| DraftStore.Upsert | p99 | 126ms | 163ms | 37ms | 29.25
| LinkMetadataStore.Get | p99 | 95ms | 122ms | 27ms | 28.48
| ChannelStore.SaveMember | p99 | 446ms | 570ms | 124ms | 27.81
| PreferenceStore.GetAll | p99 | 89ms | 113ms | 24ms | 26.97
| ChannelStore.AutocompleteInTeamForSearch | p99 | 487ms | 618ms | 131ms | 26.89
| UserStore.GetProfilesByUsernames | p99 | 131ms | 166ms | 35ms | 26.81
| ThreadStore.GetThreadsForUser | p99 | 144ms | 182ms | 38ms | 26.32
| ProductNoticesStore.View | p99 | 565ms | 713ms | 148ms | 26.17
| StatusStore.Get | p99 | 96ms | 121ms | 25ms | 26.12
| ChannelStore.Get | p99 | 182ms | 227ms | 45ms | 24.76
| PostStore.GetPostsBefore | p99 | 141ms | 175ms | 34ms | 24.15
| PostAcknowledgementStore.GetForPost | p99 | 112ms | 139ms | 27ms | 24.03
| DraftStore.Get | p99 | 156ms | 193ms | 37ms | 23.77
| PostStore.GetPosts | p99 | 74ms | 91ms | 17ms | 22.86
| PostStore.GetPostIdAfterTime | p99 | 65ms | 79ms | 14ms | 21.43
| UserStore.GetAllProfiles | p99 | 61ms | 74ms | 13ms | 21.36
| ThreadStore.GetTeamsUnreadForUser | p99 | 143ms | 173ms | 30ms | 21.05
| ChannelStore.GetFileCount | p99 | 110ms | 133ms | 23ms | 20.94
| ChannelStore.CreateInitialSidebarCategories | p99 | 424ms | 510ms | 86ms | 20.27
| ChannelStore.GetMemberLastViewedAt | p99 | 79ms | 94ms | 15ms | 19.00
| GroupStore.GetGroups | p99 | 95ms | 113ms | 18ms | 18.89
| ChannelStore.GetMemberForPost | p99 | 163ms | 193ms | 30ms | 18.40
| PostStore.GetSingle | p99 | 93ms | 110ms | 17ms | 18.25
| TeamStore.GetMember | p99 | 39ms | 46ms | 7ms | 18.05
| ThreadStore.GetThreadFollowers | p99 | 89ms | 105ms | 16ms | 17.94
| WebhookStore.GetOutgoingByTeam | p99 | 159ms | 186ms | 27ms | 16.93
| TeamStore.GetTeamsByUserId | p99 | 86ms | 100ms | 14ms | 16.31
| PostAcknowledgementStore.GetForPosts | p99 | 171ms | 198ms | 27ms | 15.75
| PostStore.SetPostReminder | p99 | 203ms | 234ms | 31ms | 15.23
| PostPriorityStore.GetForPosts | p99 | 176ms | 202ms | 26ms | 14.76
| PostStore.Save | p99 | 338ms | 387ms | 49ms | 14.49
| PostPersistentNotificationStore.GetSingle | p99 | 83ms | 95ms | 12ms | 14.45
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 205ms | 234ms | 29ms | 14.13
| ChannelStore.GetSidebarCategory | p99 | 355ms | 405ms | 50ms | 14.08
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 86ms | 98ms | 12ms | 14.02
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 66ms | 75ms | 9ms | 13.59
| EmojiStore.GetByName | p99 | 98ms | 110ms | 12ms | 12.23
| ChannelStore.GetByName | p99 | 92ms | 103ms | 11ms | 12.01
| UserStore.GetUnreadCount | p99 | 94ms | 105ms | 11ms | 11.76
| TeamStore.GetAllPage | p99 | 87ms | 97ms | 10ms | 11.48
| PluginStore.SetWithOptions | p99 | 113ms | 126ms | 13ms | 11.46
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 90ms | 100ms | 10ms | 11.15
| ThreadStore.GetThreadForUser | p99 | 192ms | 213ms | 21ms | 10.94
| FileInfoStore.AttachToPost | p99 | 194ms | 214ms | 20ms | 10.32
| SessionStore.Get | p99 | 195ms | 215ms | 20ms | 10.26
| TeamStore.Get | p99 | 90ms | 99ms | 9ms | 9.96
| UserTermsOfServiceStore.GetByUser | p99 | 81ms | 89ms | 8ms | 9.87
| JobStore.GetAllByStatus | p99 | 171ms | 187ms | 16ms | 9.36
| ChannelStore.GetMemberCount | p99 | 206ms | 225ms | 19ms | 9.20
| SystemStore.GetByName | p99 | 80ms | 87ms | 7ms | 8.76
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 81ms | 88ms | 7ms | 8.62
| ChannelStore.GetMember | p99 | 94ms | 102ms | 8ms | 8.48
| UserStore.Save | p99 | 353ms | 381ms | 28ms | 7.94
| ChannelStore.SearchGroupChannels | p99 | 171ms | 184ms | 13ms | 7.59
| UserStore.IsEmpty | p99 | 41ms | 44ms | 3ms | 7.36
| PreferenceStore.Save | p99 | 237ms | 254ms | 17ms | 7.17
| FileInfoStore.SetContent | p99 | 212ms | 227ms | 15ms | 7.08
| GroupStore.GetByName | p99 | 86ms | 92ms | 6ms | 6.97
| ComplianceStore.MessageExport | p99 | 211ms | 225ms | 14ms | 6.65
| ThreadStore.GetTotalUnreadThreads | p99 | 92ms | 98ms | 6ms | 6.54
| ThreadStore.GetTotalThreads | p99 | 92ms | 98ms | 6ms | 6.51
| UserStore.AutocompleteUsersInChannel | p99 | 369ms | 393ms | 24ms | 6.51
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 92ms | 98ms | 6ms | 6.51
| PostStore.Get | p99 | 229ms | 243ms | 14ms | 6.12
| ChannelStore.GetPublicChannelsForTeam | p99 | 226ms | 239ms | 13ms | 5.76
| PostStore.GetPostsSince | p99 | 212ms | 224ms | 12ms | 5.66
| ThreadStore.GetTotalUnreadMentions | p99 | 92ms | 97ms | 5ms | 5.46
| ChannelStore.IncrementMentionCount | p99 | 92ms | 97ms | 5ms | 5.45
| JobStore.UpdateStatus | p99 | 78ms | 82ms | 4ms | 5.10
| UserStore.GetAllProfilesInChannel | p99 | 2.194s | 2.305s | 111ms | 5.06
| ThreadStore.MaintainMembership | p99 | 221ms | 232ms | 11ms | 4.98
| ReactionStore.GetForPost | p99 | 87ms | 91ms | 4ms | 4.58
| ThreadStore.UpdateMembership | p99 | 89ms | 93ms | 4ms | 4.49
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 89ms | 93ms | 4ms | 4.49
| ChannelStore.UpdateLastViewedAt | p99 | 93ms | 97ms | 4ms | 4.29
| PostStore.GetPostIdBeforeTime | p99 | 94ms | 98ms | 4ms | 4.25
| ChannelStore.GetAllChannelMembersForUser | p99 | 94ms | 98ms | 4ms | 4.24
| DraftStore.Delete | p99 | 98ms | 102ms | 4ms | 4.10
| PostPriorityStore.GetForPost | p99 | 83ms | 86ms | 3ms | 3.60
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 232ms | 240ms | 8ms | 3.45
| ThreadStore.MarkAsRead | p99 | 88ms | 91ms | 3ms | 3.42
| TeamStore.GetTeamsForUser | p99 | 89ms | 92ms | 3ms | 3.38
| SessionStore.UpdateLastActivityAt | p99 | 91ms | 94ms | 3ms | 3.31
| ChannelStore.Autocomplete | p99 | 236ms | 243ms | 7ms | 2.97
| ChannelStore.UpdateSidebarCategories | p99 | 1.585s | 1.63s | 45ms | 2.84
| UserStore.Search | p99 | 235ms | 241ms | 6ms | 2.55
| UserStore.UpdateFailedPasswordAttempts | p99 | 86ms | 88ms | 2ms | 2.33
| UserStore.Get | p99 | 89ms | 91ms | 2ms | 2.26
| StatusStore.UpdateLastActivityAt | p99 | 90ms | 92ms | 2ms | 2.21
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 11ms | 0s | -11ms | -103.17
| ProductNoticesStore.GetViews | avg | 4ms | 1ms | -3ms | -75.87
| SessionStore.GetSessionsExpired | avg | 10ms | 3ms | -7ms | -73.27
| TeamStore.AnalyticsTeamCount | avg | 6ms | 2ms | -4ms | -71.02
| StatusStore.SaveOrUpdate | avg | 26ms | 12ms | -14ms | -54.25
| StatusStore.UpdateExpiredDNDStatuses | avg | 12ms | 6ms | -6ms | -51.96
| ChannelStore.CreateSidebarCategory | avg | 63ms | 32ms | -31ms | -49.58
| JobStore.UpdateStatusOptimistically | avg | 14ms | 8ms | -6ms | -43.55
| UserStore.AnalyticsActiveCount | avg | 61ms | 37ms | -24ms | -39.03
| ChannelStore.GetMembers | avg | 8ms | 5ms | -3ms | -38.16
| ThreadStore.MarkAllAsReadByTeam | avg | 13ms | 8ms | -5ms | -38.04
| PostStore.Delete | avg | 43ms | 27ms | -16ms | -37.37
| UserStore.Count | avg | 33ms | 21ms | -12ms | -36.31
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 38ms | 26ms | -12ms | -31.73
| ChannelStore.GetTeamChannels | avg | 79ms | 55ms | -24ms | -30.19
| ChannelStore.GetMembersForUserWithPagination | avg | 16ms | 12ms | -4ms | -25.19
| ThreadStore.MarkAllAsReadByChannels | avg | 8ms | 6ms | -2ms | -24.32
| JobStore.UpdateStatus | avg | 8ms | 6ms | -2ms | -24.25
| ChannelStore.GetChannelUnread | avg | 8ms | 6ms | -2ms | -24.15
| ChannelStore.CreateInitialSidebarCategories | avg | 50ms | 38ms | -12ms | -23.78
| ChannelStore.SearchGroupChannels | avg | 18ms | 14ms | -4ms | -21.75
| SessionStore.Save | avg | 12ms | 10ms | -2ms | -17.32
| RoleStore.ChannelHigherScopedPermissions | avg | 12ms | 10ms | -2ms | -16.54
| PostStore.Update | avg | 31ms | 27ms | -4ms | -12.73
| UserStore.Update | avg | 22ms | 20ms | -2ms | -9.25
| ChannelStore.AutocompleteInTeamForSearch | avg | 106ms | 97ms | -9ms | -8.52
| ChannelStore.Save | avg | 39ms | 36ms | -3ms | -7.77
| ProductNoticesStore.ClearOldNotices | avg | 31ms | 29ms | -2ms | -6.48
| ChannelStore.UpdateSidebarCategories | avg | 132ms | 125ms | -7ms | -5.32
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 130ms | 124ms | -6ms | -4.61
| ChannelStore.CreateDirectChannel | avg | 71ms | 68ms | -3ms | -4.23
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 94ms | 0s | -94ms | -100.00
| ChannelStore.CreateSidebarCategory | p99 | 477ms | 50ms | -427ms | -89.42
| UserStore.AnalyticsActiveCount | p99 | 246ms | 50ms | -196ms | -79.84
| TeamStore.AnalyticsTeamCount | p99 | 24ms | 5ms | -19ms | -77.87
| UserStore.Count | p99 | 208ms | 49ms | -159ms | -76.44
| JobStore.UpdateStatusOptimistically | p99 | 283ms | 98ms | -185ms | -65.49
| StatusStore.UpdateExpiredDNDStatuses | p99 | 226ms | 81ms | -145ms | -64.16
| StatusStore.SaveOrUpdate | p99 | 479ms | 180ms | -299ms | -62.47
| UserStore.GetMany | p99 | 208ms | 92ms | -116ms | -55.77
| PluginStore.Get | p99 | 10ms | 5ms | -5ms | -51.02
| ProductNoticesStore.GetViews | p99 | 10ms | 5ms | -5ms | -50.51
| ChannelStore.GetMembersForUserWithPagination | p99 | 96ms | 48ms | -48ms | -49.87
| ChannelStore.GetMembers | p99 | 48ms | 24ms | -24ms | -49.74
| SessionStore.GetSessionsExpired | p99 | 48ms | 24ms | -24ms | -49.61
| ChannelStore.AnalyticsTypeCount | p99 | 49ms | 25ms | -24ms | -49.40
| ChannelStore.GetTeamChannels | p99 | 472ms | 243ms | -229ms | -48.47
| UserStore.GetByUsername | p99 | 168ms | 112ms | -56ms | -33.33
| PostStore.Update | p99 | 323ms | 226ms | -97ms | -30.00
| ChannelStore.GetChannelsByUser | p99 | 130ms | 99ms | -31ms | -23.89
| PluginStore.Delete | p99 | 59ms | 50ms | -9ms | -15.20
| PluginStore.List | p99 | 154ms | 133ms | -21ms | -13.64
| SessionStore.GetLRUSessions | p99 | 81ms | 73ms | -8ms | -9.84
| SessionStore.Save | p99 | 148ms | 137ms | -11ms | -7.43
| ThreadStore.MarkAllAsReadByChannels | p99 | 96ms | 89ms | -7ms | -7.26
| UserStore.UpdateLastLogin | p99 | 70ms | 65ms | -5ms | -7.12
| RoleStore.ChannelHigherScopedPermissions | p99 | 50ms | 47ms | -3ms | -6.06
| UserStore.Update | p99 | 220ms | 212ms | -8ms | -3.64
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 476ms | 469ms | -7ms | -1.47
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | avg | 3ms | 18ms | 15ms | 579.80
| getJobsByType | avg | 15ms | 26ms | 11ms | 73.56
| unfollowThreadByUser | avg | 44ms | 56ms | 12ms | 27.37
| getUser | avg | 10ms | 12ms | 2ms | 19.51
| getPostsForChannelAroundLastUnread | avg | 36ms | 43ms | 7ms | 19.36
| getTeamsUnreadForUser | avg | 12ms | 14ms | 2ms | 16.60
| updatePreferences | avg | 33ms | 38ms | 5ms | 15.30
| getPostThread | avg | 49ms | 54ms | 5ms | 10.30
| getPublicChannelsForTeam | avg | 32ms | 35ms | 3ms | 9.37
| updateCategoriesForTeamForUser | avg | 203ms | 221ms | 18ms | 8.89
| getPostsForChannel | avg | 92ms | 100ms | 8ms | 8.69
| createGroupChannel | avg | 785ms | 848ms | 63ms | 8.02
| setPostReminder | avg | 53ms | 57ms | 4ms | 7.52
| searchAllChannels | avg | 57ms | 61ms | 4ms | 6.99
| addChannelMember | avg | 514ms | 538ms | 24ms | 4.67
| getTeamStats | avg | 74ms | 77ms | 3ms | 4.06
| searchUsers | avg | 56ms | 58ms | 2ms | 3.55
| autocompleteUsers | avg | 68ms | 70ms | 2ms | 2.92
| updateReadStateThreadByUser | avg | 113ms | 116ms | 3ms | 2.65
| createUser | avg | 258ms | 264ms | 6ms | 2.33
| addTeamMember | avg | 1.317s | 1.345s | 28ms | 2.13
| uploadFileStream | avg | 455ms | 463ms | 8ms | 1.76
| searchPostsInTeam | avg | 314ms | 319ms | 5ms | 1.59
| createDirectChannel | avg | 587ms | 596ms | 9ms | 1.53
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 10ms | 25ms | 15ms | 153.06
| listChannelBookmarksForChannel | p99 | 48ms | 94ms | 46ms | 96.34
| updateReadStateAllThreadsByUser | p99 | 25ms | 48ms | 23ms | 92.84
| getJobsByType | p99 | 125ms | 214ms | 89ms | 70.92
| unfollowThreadByUser | p99 | 392ms | 620ms | 228ms | 58.18
| getPostsForChannel | p99 | 994ms | 1.431s | 437ms | 43.96
| getPreferences | p99 | 93ms | 130ms | 37ms | 39.83
| getFileThumbnail | p99 | 267ms | 371ms | 104ms | 39.01
| addChannelMember | p99 | 2.482s | 3.42s | 938ms | 37.79
| getAllTeams | p99 | 106ms | 142ms | 36ms | 34.00
| getPostThread | p99 | 463ms | 618ms | 155ms | 33.48
| getChannelMembersForTeamForUser | p99 | 125ms | 166ms | 41ms | 32.74
| getPostsForChannelAroundLastUnread | p99 | 448ms | 585ms | 137ms | 30.60
| autocompleteChannelsForTeamForSearch | p99 | 487ms | 618ms | 131ms | 26.89
| saveReaction | p99 | 289ms | 366ms | 77ms | 26.65
| getChannelsForTeamForUser | p99 | 141ms | 176ms | 35ms | 24.88
| searchPostsInTeam | p99 | 3.48s | 4.32s | 840ms | 24.14
| addTeamMember | p99 | 7.181s | 8.863s | 1.682s | 23.42
| getUsersByNames | p99 | 142ms | 173ms | 31ms | 21.91
| getChannel | p99 | 218ms | 264ms | 46ms | 21.05
| getTeamsForUser | p99 | 88ms | 105ms | 17ms | 19.39
| deleteDraft | p99 | 170ms | 201ms | 31ms | 18.23
| updatePreferences | p99 | 363ms | 429ms | 66ms | 18.18
| getThreadsForUser | p99 | 162ms | 191ms | 29ms | 17.93
| getTeamsUnreadForUser | p99 | 190ms | 220ms | 30ms | 15.80
| getTeamMember | p99 | 159ms | 183ms | 24ms | 15.12
| getDrafts | p99 | 164ms | 188ms | 24ms | 14.59
| getUser | p99 | 204ms | 232ms | 28ms | 13.71
| upsertDraft | p99 | 184ms | 207ms | 23ms | 12.47
| getPublicChannelsForTeam | p99 | 226ms | 253ms | 27ms | 11.96
| getTeamMembersForUser | p99 | 126ms | 139ms | 13ms | 10.34
| getUsers | p99 | 203ms | 224ms | 21ms | 10.33
| getUserStatusesByIds | p99 | 41ms | 45ms | 4ms | 9.77
| updateReadStateThreadByUser | p99 | 861ms | 945ms | 84ms | 9.75
| autocompleteUsers | p99 | 344ms | 377ms | 33ms | 9.59
| viewChannel | p99 | 419ms | 458ms | 39ms | 9.30
| searchGroupChannels | p99 | 174ms | 187ms | 13ms | 7.49
| createUser | p99 | 1.893s | 2.001s | 108ms | 5.70
| createGroupChannel | p99 | 4.458s | 4.7s | 242ms | 5.43
| getUsersByIds | p99 | 39ms | 41ms | 2ms | 5.07
| getChannelStats | p99 | 99ms | 104ms | 5ms | 5.05
| getFilePreview | p99 | 402ms | 421ms | 19ms | 4.73
| getChannelMember | p99 | 214ms | 224ms | 10ms | 4.67
| createPost | p99 | 4.632s | 4.83s | 198ms | 4.27
| getClientConfig | p99 | 228ms | 237ms | 9ms | 3.94
| getCategoriesForTeamForUser | p99 | 233ms | 241ms | 8ms | 3.43
| searchAllChannels | p99 | 237ms | 244ms | 7ms | 2.95
| createDirectChannel | p99 | 2.415s | 2.478s | 63ms | 2.61
| searchUsers | p99 | 238ms | 243ms | 5ms | 2.11
| removeUserCustomStatus | p99 | 1.907s | 1.94s | 33ms | 1.73
| uploadFileStream | p99 | 2.072s | 2.102s | 30ms | 1.45
| getProfileImage | p99 | 463ms | 468ms | 5ms | 1.08
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateCategoryForTeamForUser | avg | 194ms | 0s | -194ms | -100.07
| channelMemberCountsByGroup | avg | 11ms | 0s | -11ms | -99.92
| getFilteredUsersStats | avg | 31ms | 0s | -31ms | -99.76
| getUsersByGroupChannelIds | avg | 6ms | 0s | -6ms | -93.88
| getAnalytics | avg | 350ms | 70ms | -280ms | -79.93
| getChannelMembers | avg | 15ms | 6ms | -9ms | -58.23
| followThreadByUser | avg | 87ms | 40ms | -47ms | -53.79
| logout | avg | 214ms | 111ms | -103ms | -48.14
| login | avg | 178ms | 99ms | -79ms | -44.47
| createCategoryForTeamForUser | avg | 76ms | 44ms | -32ms | -42.35
| getChannelUnread | avg | 10ms | 6ms | -4ms | -42.07
| deletePost | avg | 67ms | 39ms | -28ms | -41.99
| getRolesByNames | avg | 7ms | 4ms | -3ms | -40.26
| getCategoriesForTeamForUser | avg | 38ms | 26ms | -12ms | -31.43
| updateReadStateAllThreadsByUser | avg | 13ms | 9ms | -4ms | -30.22
| searchGroupChannels | avg | 19ms | 14ms | -5ms | -26.87
| patchPost | avg | 110ms | 86ms | -24ms | -21.87
| getChannelsForUser | avg | 10ms | 8ms | -2ms | -20.99
| getChannelMembersForUser | avg | 11ms | 9ms | -2ms | -18.43
| createChannel | avg | 430ms | 375ms | -55ms | -12.79
| autocompleteChannelsForTeamForSearch | avg | 106ms | 97ms | -9ms | -8.52
| getProfileImage | avg | 81ms | 76ms | -5ms | -6.15
| createPost | avg | 796ms | 775ms | -21ms | -2.64
| removeUserCustomStatus | avg | 373ms | 368ms | -5ms | -1.34
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | p99 | 5ms | 0s | -5ms | -100.95
| getFilteredUsersStats | p99 | 50ms | 0s | -50ms | -100.82
| getUsersByGroupChannelIds | p99 | 10ms | 0s | -10ms | -100.50
| updateCategoryForTeamForUser | p99 | 249ms | 0s | -249ms | -100.20
| channelMemberCountsByGroup | p99 | 94ms | 0s | -94ms | -100.00
| getAnalytics | p99 | 990ms | 100ms | -890ms | -89.90
| createCategoryForTeamForUser | p99 | 477ms | 99ms | -378ms | -79.16
| logout | p99 | 2.185s | 473ms | -1.712s | -78.35
| getChannelMembers | p99 | 96ms | 24ms | -72ms | -74.61
| getRolesByNames | p99 | 95ms | 25ms | -70ms | -73.68
| login | p99 | 1.708s | 842ms | -866ms | -50.69
| patchPost | p99 | 1.45s | 804ms | -646ms | -44.55
| getChannelsForUser | p99 | 134ms | 101ms | -33ms | -24.64
| getChannelUnread | p99 | 116ms | 98ms | -18ms | -15.58
| followThreadByUser | p99 | 479ms | 407ms | -72ms | -15.03
| deletePost | p99 | 445ms | 425ms | -20ms | -4.49
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 86ms | 0s | 0.000
| BotStore.Get |  Avg| 5ms| 6ms | 1ms | 20.054
| |  P99| 42ms| 81ms | 39ms | 92.857
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 7ms| 11ms | 4ms | 59.338
| |  P99| 24ms| 96ms | 72ms | 296.908
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 130ms| 124ms | -6ms | -4.607
| |  P99| 476ms| 469ms | -7ms | -1.470
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 6ms | 1ms | 19.035
| |  P99| 66ms| 75ms | 9ms | 13.591
| ChannelStore.AnalyticsTypeCount |  Avg| 15ms| 16ms | 1ms | 6.579
| |  P99| 49ms| 25ms | -24ms | -49.398
| ChannelStore.Autocomplete |  Avg| 56ms| 60ms | 4ms | 7.082
| |  P99| 236ms| 243ms | 7ms | 2.969
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 106ms| 97ms | -9ms | -8.525
| |  P99| 487ms| 618ms | 131ms | 26.895
| ChannelStore.CreateDirectChannel |  Avg| 71ms| 68ms | -3ms | -4.229
| |  P99| 608ms| 792ms | 184ms | 30.263
| ChannelStore.CreateInitialSidebarCategories |  Avg| 50ms| 38ms | -12ms | -23.778
| |  P99| 424ms| 510ms | 86ms | 20.271
| ChannelStore.CreateSidebarCategory |  Avg| 63ms| 32ms | -31ms | -49.576
| |  P99| 477ms| 50ms | -427ms | -89.425
| ChannelStore.Get |  Avg| 15ms| 19ms | 4ms | 26.679
| |  P99| 182ms| 227ms | 45ms | 24.758
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 28ms| 30ms | 2ms | 7.210
| |  P99| 205ms| 234ms | 29ms | 14.132
| ChannelStore.GetAllChannelMembersForUser |  Avg| 10ms| 11ms | 1ms | 9.729
| |  P99| 94ms| 98ms | 4ms | 4.237
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 29ms| 32ms | 3ms | 10.317
| |  P99| 279ms| 365ms | 86ms | 30.806
| ChannelStore.GetByName |  Avg| 8ms| 10ms | 2ms | 23.582
| |  P99| 92ms| 103ms | 11ms | 12.007
| ChannelStore.GetChannelUnread |  Avg| 8ms| 6ms | -2ms | -24.150
| |  P99| 96ms| 97ms | 1ms | 1.045
| ChannelStore.GetChannels |  Avg| 10ms| 11ms | 1ms | 9.968
| |  P99| 129ms| 168ms | 39ms | 30.281
| ChannelStore.GetChannelsByUser |  Avg| 9ms| 8ms | -1ms | -10.704
| |  P99| 130ms| 99ms | -31ms | -23.888
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 98ms| 135ms | 37ms | 37.806
| ChannelStore.GetFileCount |  Avg| 11ms| 12ms | 1ms | 9.195
| |  P99| 110ms| 133ms | 23ms | 20.944
| ChannelStore.GetGuestCount |  Avg| 8ms| 9ms | 1ms | 12.631
| |  P99| 95ms| 135ms | 40ms | 42.281
| ChannelStore.GetMember |  Avg| 7ms| 8ms | 1ms | 13.367
| |  P99| 94ms| 102ms | 8ms | 8.478
| ChannelStore.GetMemberCount |  Avg| 36ms| 38ms | 2ms | 5.602
| |  P99| 206ms| 225ms | 19ms | 9.205
| ChannelStore.GetMemberCountsByGroup |  Avg| 11ms| 0s | -11ms | -103.173
| |  P99| 94ms| 0s | -94ms | -100.001
| ChannelStore.GetMemberForPost |  Avg| 15ms| 16ms | 1ms | 6.632
| |  P99| 163ms| 193ms | 30ms | 18.402
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 6ms | 1ms | 20.004
| |  P99| 79ms| 94ms | 15ms | 19.005
| ChannelStore.GetMembers |  Avg| 8ms| 5ms | -3ms | -38.158
| |  P99| 48ms| 24ms | -24ms | -49.742
| ChannelStore.GetMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 117ms| 159ms | 42ms | 35.903
| ChannelStore.GetMembersForUserWithPagination |  Avg| 16ms| 12ms | -4ms | -25.187
| |  P99| 96ms| 48ms | -48ms | -49.870
| ChannelStore.GetPinnedPostCount |  Avg| 8ms| 9ms | 1ms | 11.783
| |  P99| 93ms| 133ms | 40ms | 42.789
| ChannelStore.GetPublicChannelsForTeam |  Avg| 30ms| 33ms | 3ms | 9.906
| |  P99| 226ms| 239ms | 13ms | 5.757
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 38ms| 26ms | -12ms | -31.732
| |  P99| 232ms| 240ms | 8ms | 3.447
| ChannelStore.GetSidebarCategory |  Avg| 29ms| 40ms | 11ms | 37.475
| |  P99| 355ms| 405ms | 50ms | 14.085
| ChannelStore.GetTeamChannels |  Avg| 79ms| 55ms | -24ms | -30.190
| |  P99| 472ms| 243ms | -229ms | -48.466
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 97ms | 5ms | 5.450
| ChannelStore.Save |  Avg| 39ms| 36ms | -3ms | -7.771
| |  P99| 396ms| 393ms | -3ms | -0.758
| ChannelStore.SaveMember |  Avg| 50ms| 56ms | 6ms | 12.028
| |  P99| 446ms| 570ms | 124ms | 27.812
| ChannelStore.SearchGroupChannels |  Avg| 18ms| 14ms | -4ms | -21.748
| |  P99| 171ms| 184ms | 13ms | 7.589
| ChannelStore.UpdateLastViewedAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 97ms | 4ms | 4.286
| ChannelStore.UpdateSidebarCategories |  Avg| 132ms| 125ms | -7ms | -5.320
| |  P99| 1.585s| 1.63s | 45ms | 2.839
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 8ms | 1ms | 15.118
| |  P99| 86ms| 98ms | 12ms | 14.024
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 12ms| 13ms | 1ms | 8.671
| |  P99| 137ms| 188ms | 51ms | 37.226
| CommandWebhookStore.Cleanup |  Avg| 1ms| 12ms | 11ms | 1464.129
| |  P99| 5ms| 48ms | 43ms | 868.486
| ComplianceStore.MessageExport |  Avg| 17ms| 18ms | 1ms | 5.894
| |  P99| 211ms| 225ms | 14ms | 6.646
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 102ms | 4ms | 4.101
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 89ms| 93ms | 4ms | 4.493
| DraftStore.Get |  Avg| 12ms| 13ms | 1ms | 8.681
| |  P99| 156ms| 193ms | 37ms | 23.771
| DraftStore.GetDraftsForUser |  Avg| 11ms| 13ms | 2ms | 17.564
| |  P99| 135ms| 179ms | 44ms | 32.492
| DraftStore.Upsert |  Avg| 11ms| 12ms | 1ms | 8.759
| |  P99| 126ms| 163ms | 37ms | 29.254
| EmojiStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 98ms| 110ms | 12ms | 12.233
| EmojiStore.GetMultipleByName |  Avg| 1ms| 2ms | 1ms | 71.898
| |  P99| 5ms| 23ms | 18ms | 363.636
| FileInfoStore.AttachToPost |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 194ms| 214ms | 20ms | 10.323
| FileInfoStore.Get |  Avg| 9ms| 10ms | 1ms | 10.567
| |  P99| 120ms| 158ms | 38ms | 31.551
| FileInfoStore.GetByIds |  Avg| 9ms| 10ms | 1ms | 11.674
| |  P99| 92ms| 144ms | 52ms | 56.690
| FileInfoStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 100ms| 152ms | 52ms | 52.176
| FileInfoStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 116ms| 157ms | 41ms | 35.211
| FileInfoStore.SetContent |  Avg| 19ms| 20ms | 1ms | 5.167
| |  P99| 212ms| 227ms | 15ms | 7.085
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 5ms | 1ms | 23.516
| |  P99| 69ms| 90ms | 21ms | 30.516
| GroupStore.GetByName |  Avg| 5ms| 6ms | 1ms | 18.346
| |  P99| 86ms| 92ms | 6ms | 6.972
| GroupStore.GetGroups |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 113ms | 18ms | 18.893
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 19ms| 18ms | -1ms | -5.254
| |  P99| 219ms| 219ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 171ms| 187ms | 16ms | 9.363
| JobStore.GetAllByTypePage |  Avg| 15ms| 26ms | 11ms | 75.609
| |  P99| 124ms| 214ms | 90ms | 72.588
| JobStore.GetCountByStatusAndType |  Avg| 10ms| 12ms | 2ms | 20.357
| |  P99| 101ms| 196ms | 95ms | 93.596
| JobStore.GetNewestJobByStatusesAndType |  Avg| 6ms| 9ms | 3ms | 51.061
| |  P99| 48ms| 185ms | 137ms | 284.306
| JobStore.Save |  Avg| 8ms| 10ms | 2ms | 25.101
| |  P99| 57ms| 170ms | 113ms | 198.246
| JobStore.UpdateOptimistically |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 120ms| 164ms | 44ms | 36.676
| JobStore.UpdateStatus |  Avg| 8ms| 6ms | -2ms | -24.246
| |  P99| 78ms| 82ms | 4ms | 5.096
| JobStore.UpdateStatusOptimistically |  Avg| 14ms| 8ms | -6ms | -43.550
| |  P99| 283ms| 98ms | -185ms | -65.487
| LicenseStore.GetAll |  Avg| 2ms| 9ms | 7ms | 354.662
| |  P99| 10ms| 25ms | 15ms | 153.846
| LinkMetadataStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 95ms| 122ms | 27ms | 28.478
| LinkMetadataStore.Save |  Avg| 5ms| 7ms | 2ms | 37.483
| |  P99| 44ms| 80ms | 36ms | 80.899
| PluginStore.Delete |  Avg| 4ms| 3ms | -1ms | -24.723
| |  P99| 59ms| 50ms | -9ms | -15.195
| PluginStore.Get |  Avg| 2ms| 1ms | -1ms | -47.301
| |  P99| 10ms| 5ms | -5ms | -51.020
| PluginStore.List |  Avg| 8ms| 9ms | 1ms | 13.133
| |  P99| 154ms| 133ms | -21ms | -13.636
| PluginStore.SetWithOptions |  Avg| 9ms| 8ms | -1ms | -10.877
| |  P99| 113ms| 126ms | 13ms | 11.455
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 112ms| 139ms | 27ms | 24.027
| PostAcknowledgementStore.GetForPosts |  Avg| 10ms| 11ms | 1ms | 9.694
| |  P99| 171ms| 198ms | 27ms | 15.750
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 6ms | 2ms | 45.280
| |  P99| 74ms| 155ms | 81ms | 110.204
| PostPersistentNotificationStore.Get |  Avg| 6ms| 8ms | 2ms | 35.471
| |  P99| 74ms| 198ms | 124ms | 168.707
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 7ms | 1ms | 15.875
| |  P99| 83ms| 95ms | 12ms | 14.450
| PostPriorityStore.GetForPost |  Avg| 7ms| 6ms | -1ms | -15.161
| |  P99| 83ms| 86ms | 3ms | 3.601
| PostPriorityStore.GetForPosts |  Avg| 11ms| 12ms | 1ms | 9.175
| |  P99| 176ms| 202ms | 26ms | 14.758
| PostStore.AnalyticsPostCount |  Avg| 306ms| 679ms | 373ms | 121.795
| |  P99| 496ms| 993ms | 497ms | 100.151
| PostStore.Delete |  Avg| 43ms| 27ms | -16ms | -37.369
| |  P99| 242ms| 425ms | 183ms | 75.698
| PostStore.Get |  Avg| 20ms| 22ms | 2ms | 9.794
| |  P99| 229ms| 243ms | 14ms | 6.116
| PostStore.GetEtag |  Avg| 10ms| 11ms | 1ms | 10.440
| |  P99| 107ms| 170ms | 63ms | 58.938
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 5ms | 1ms | 23.446
| |  P99| 65ms| 79ms | 14ms | 21.429
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 8ms | 1ms | 13.550
| |  P99| 94ms| 98ms | 4ms | 4.251
| PostStore.GetPostReminderMetadata |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 85ms| 124ms | 39ms | 46.019
| PostStore.GetPostReminders |  Avg| 9ms| 13ms | 4ms | 45.042
| |  P99| 47ms| 221ms | 174ms | 366.960
| PostStore.GetPosts |  Avg| 6ms| 7ms | 1ms | 16.032
| |  P99| 74ms| 91ms | 17ms | 22.860
| PostStore.GetPostsAfter |  Avg| 9ms| 8ms | -1ms | -11.449
| |  P99| 89ms| 90ms | 1ms | 1.126
| PostStore.GetPostsBefore |  Avg| 12ms| 13ms | 1ms | 8.305
| |  P99| 141ms| 175ms | 34ms | 24.152
| PostStore.GetPostsByThread |  Avg| 13ms| 14ms | 1ms | 7.425
| |  P99| 97ms| 129ms | 32ms | 32.981
| PostStore.GetPostsSince |  Avg| 26ms| 27ms | 1ms | 3.850
| |  P99| 212ms| 224ms | 12ms | 5.661
| PostStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 110ms | 17ms | 18.252
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 29ms| 31ms | 2ms | 6.833
| |  P99| 338ms| 387ms | 49ms | 14.494
| PostStore.SearchPostsForUser |  Avg| 296ms| 299ms | 3ms | 1.014
| |  P99| 2.974s| 4.23s | 1.256s | 42.238
| PostStore.SetPostReminder |  Avg| 16ms| 24ms | 8ms | 49.728
| |  P99| 203ms| 234ms | 31ms | 15.234
| PostStore.Update |  Avg| 31ms| 27ms | -4ms | -12.734
| |  P99| 323ms| 226ms | -97ms | -30.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 8ms| 9ms | 1ms | 12.988
| |  P99| 44ms| 205ms | 161ms | 361.802
| PreferenceStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 122ms| 165ms | 43ms | 35.195
| PreferenceStore.GetAll |  Avg| 7ms| 8ms | 1ms | 15.212
| |  P99| 89ms| 113ms | 24ms | 26.970
| PreferenceStore.Save |  Avg| 20ms| 22ms | 2ms | 10.159
| |  P99| 237ms| 254ms | 17ms | 7.171
| ProductNoticesStore.ClearOldNotices |  Avg| 31ms| 29ms | -2ms | -6.484
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 4ms| 1ms | -3ms | -75.871
| |  P99| 10ms| 5ms | -5ms | -50.505
| ProductNoticesStore.View |  Avg| 54ms| 54ms | 0s | 0.000
| |  P99| 565ms| 713ms | 148ms | 26.173
| ReactionStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 87ms| 91ms | 4ms | 4.581
| RetentionPolicyStore.GetAll |  Avg| 6ms| 26ms | 20ms | 353.497
| |  P99| 10ms| 99ms | 89ms | 894.472
| RetentionPolicyStore.GetCount |  Avg| 9ms| 24ms | 15ms | 160.206
| |  P99| 10ms| 50ms | 40ms | 402.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 12ms| 10ms | -2ms | -16.540
| |  P99| 50ms| 47ms | -3ms | -6.061
| RoleStore.GetByNames |  Avg| 13ms| 17ms | 4ms | 29.659
| |  P99| 50ms| 155ms | 105ms | 210.759
| SchemeStore.GetAllPage |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 13ms| 14ms | 1ms | 7.849
| |  P99| 195ms| 215ms | 20ms | 10.258
| SessionStore.GetLRUSessions |  Avg| 6ms| 5ms | -1ms | -18.101
| |  P99| 81ms| 73ms | -8ms | -9.835
| SessionStore.GetSessionsExpired |  Avg| 10ms| 3ms | -7ms | -73.266
| |  P99| 48ms| 24ms | -24ms | -49.612
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 6ms| 7ms | 1ms | 15.589
| |  P99| 81ms| 88ms | 7ms | 8.622
| SessionStore.Remove |  Avg| 5ms| 8ms | 3ms | 58.996
| |  P99| 46ms| 73ms | 27ms | 58.065
| SessionStore.Save |  Avg| 12ms| 10ms | -2ms | -17.320
| |  P99| 148ms| 137ms | -11ms | -7.435
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 94ms | 3ms | 3.307
| StatusStore.Get |  Avg| 7ms| 8ms | 1ms | 15.157
| |  P99| 96ms| 121ms | 25ms | 26.125
| StatusStore.GetByIds |  Avg| 12ms| 14ms | 2ms | 16.534
| |  P99| 153ms| 200ms | 47ms | 30.747
| StatusStore.SaveOrUpdate |  Avg| 26ms| 12ms | -14ms | -54.245
| |  P99| 479ms| 180ms | -299ms | -62.471
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 12ms| 6ms | -6ms | -51.958
| |  P99| 226ms| 81ms | -145ms | -64.159
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 92ms | 2ms | 2.215
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 80ms| 87ms | 7ms | 8.756
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 2ms | -4ms | -71.017
| |  P99| 24ms| 5ms | -19ms | -77.867
| TeamStore.Get |  Avg| 7ms| 8ms | 1ms | 14.445
| |  P99| 90ms| 99ms | 9ms | 9.964
| TeamStore.GetActiveMemberCount |  Avg| 73ms| 75ms | 2ms | 2.727
| |  P99| 242ms| 243ms | 1ms | 0.414
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 87ms| 97ms | 10ms | 11.482
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 90ms| 100ms | 10ms | 11.147
| TeamStore.GetMember |  Avg| 2ms| 3ms | 1ms | 43.280
| |  P99| 39ms| 46ms | 7ms | 18.052
| TeamStore.GetTeamsByUserId |  Avg| 6ms| 7ms | 1ms | 17.729
| |  P99| 86ms| 100ms | 14ms | 16.306
| TeamStore.GetTeamsForUser |  Avg| 7ms| 6ms | -1ms | -15.335
| |  P99| 89ms| 92ms | 3ms | 3.377
| TeamStore.GetTotalMemberCount |  Avg| 67ms| 69ms | 2ms | 2.997
| |  P99| 234ms| 235ms | 1ms | 0.428
| TeamStore.SaveMember |  Avg| 40ms| 43ms | 3ms | 7.495
| |  P99| 243ms| 340ms | 97ms | 39.869
| ThreadStore.Get |  Avg| 9ms| 10ms | 1ms | 11.187
| |  P99| 100ms| 200ms | 100ms | 100.001
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 9ms | 1ms | 12.113
| |  P99| 98ms| 142ms | 44ms | 44.802
| ThreadStore.GetTeamsUnreadForUser |  Avg| 10ms| 11ms | 1ms | 9.963
| |  P99| 143ms| 173ms | 30ms | 21.049
| ThreadStore.GetThreadFollowers |  Avg| 7ms| 8ms | 1ms | 13.758
| |  P99| 89ms| 105ms | 16ms | 17.936
| ThreadStore.GetThreadForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 192ms| 213ms | 21ms | 10.941
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 110ms| 161ms | 51ms | 46.478
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 14ms | 1ms | 7.929
| |  P99| 144ms| 182ms | 38ms | 26.322
| ThreadStore.GetTotalThreads |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 98ms | 6ms | 6.515
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 97ms | 5ms | 5.458
| ThreadStore.GetTotalUnreadThreads |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 98ms | 6ms | 6.544
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 98ms | 6ms | 6.506
| ThreadStore.MaintainMembership |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 221ms| 232ms | 11ms | 4.979
| ThreadStore.MarkAllAsReadByChannels |  Avg| 8ms| 6ms | -2ms | -24.324
| |  P99| 96ms| 89ms | -7ms | -7.262
| ThreadStore.MarkAllAsReadByTeam |  Avg| 13ms| 8ms | -5ms | -38.036
| |  P99| 25ms| 48ms | 23ms | 92.836
| ThreadStore.MarkAsRead |  Avg| 9ms| 8ms | -1ms | -11.712
| |  P99| 88ms| 91ms | 3ms | 3.421
| ThreadStore.UpdateMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 93ms | 4ms | 4.495
| TokenStore.Cleanup |  Avg| 1ms| 16ms | 15ms | 2381.732
| |  P99| 5ms| 97ms | 92ms | 1858.586
| UserAccessTokenStore.GetByToken |  Avg| 5ms| 9ms | 4ms | 76.092
| |  P99| 47ms| 125ms | 78ms | 164.706
| UserStore.AnalyticsActiveCount |  Avg| 61ms| 37ms | -24ms | -39.027
| |  P99| 246ms| 50ms | -196ms | -79.837
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 4ms| 11ms | 7ms | 163.615
| |  P99| 10ms| 25ms | 15ms | 152.284
| UserStore.AutocompleteUsersInChannel |  Avg| 75ms| 77ms | 2ms | 2.667
| |  P99| 369ms| 393ms | 24ms | 6.508
| UserStore.Count |  Avg| 33ms| 21ms | -12ms | -36.313
| |  P99| 208ms| 49ms | -159ms | -76.442
| UserStore.Get |  Avg| 6ms| 5ms | -1ms | -17.153
| |  P99| 89ms| 91ms | 2ms | 2.255
| UserStore.GetAllProfiles |  Avg| 6ms| 7ms | 1ms | 16.572
| |  P99| 61ms| 74ms | 13ms | 21.365
| UserStore.GetAllProfilesInChannel |  Avg| 425ms| 445ms | 20ms | 4.707
| |  P99| 2.194s| 2.305s | 111ms | 5.058
| UserStore.GetByUsername |  Avg| 9ms| 10ms | 1ms | 10.939
| |  P99| 168ms| 112ms | -56ms | -33.333
| UserStore.GetForLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.113
| UserStore.GetMany |  Avg| 9ms| 10ms | 1ms | 11.573
| |  P99| 208ms| 92ms | -116ms | -55.769
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 6ms| 26ms | 20ms | 334.787
| |  P99| 10ms| 50ms | 40ms | 402.010
| UserStore.GetProfileByIds |  Avg| 10ms| 11ms | 1ms | 10.257
| |  P99| 115ms| 170ms | 55ms | 47.635
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 11ms | 1ms | 9.679
| |  P99| 131ms| 166ms | 35ms | 26.809
| UserStore.GetProfilesInChannel |  Avg| 5ms| 56ms | 51ms | 972.866
| |  P99| 24ms| 476ms | 452ms | 1869.615
| UserStore.GetProfilesNotInChannel |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 49ms| 95ms | 46ms | 93.283
| UserStore.GetUnreadCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 94ms| 105ms | 11ms | 11.758
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 44ms | 3ms | 7.356
| UserStore.Save |  Avg| 85ms| 86ms | 1ms | 1.175
| |  P99| 353ms| 381ms | 28ms | 7.938
| UserStore.Search |  Avg| 54ms| 56ms | 2ms | 3.712
| |  P99| 235ms| 241ms | 6ms | 2.553
| UserStore.Update |  Avg| 22ms| 20ms | -2ms | -9.252
| |  P99| 220ms| 212ms | -8ms | -3.635
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 7ms | -1ms | -13.327
| |  P99| 86ms| 88ms | 2ms | 2.325
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 70ms| 65ms | -5ms | -7.117
| UserStore.UpdateUpdateAt |  Avg| 7ms| 8ms | 1ms | 14.447
| |  P99| 61ms| 81ms | 20ms | 32.596
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 81ms| 89ms | 8ms | 9.873
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 13ms | 1ms | 8.026
| |  P99| 159ms| 186ms | 27ms | 16.929
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 514ms| 538ms | 24ms | 4.672
| | P99| 2.482s| 3.42s | 938ms | 37.792
| addTeamMember | Avg| 1.317s| 1.345s | 28ms | 2.126
| | P99| 7.181s| 8.863s | 1.682s | 23.422
| autocompleteChannelsForTeamForSearch | Avg| 106ms| 97ms | -9ms | -8.518
| | P99| 487ms| 618ms | 131ms | 26.895
| autocompleteUsers | Avg| 68ms| 70ms | 2ms | 2.924
| | P99| 344ms| 377ms | 33ms | 9.594
| channelMemberCountsByGroup | Avg| 11ms| 0s | -11ms | -99.920
| | P99| 94ms| 0s | -94ms | -100.001
| createCategoryForTeamForUser | Avg| 76ms| 44ms | -32ms | -42.352
| | P99| 477ms| 99ms | -378ms | -79.163
| createChannel | Avg| 430ms| 375ms | -55ms | -12.793
| | P99| 982ms| 975ms | -7ms | -0.713
| createDirectChannel | Avg| 587ms| 596ms | 9ms | 1.532
| | P99| 2.415s| 2.478s | 63ms | 2.608
| createGroupChannel | Avg| 785ms| 848ms | 63ms | 8.023
| | P99| 4.458s| 4.7s | 242ms | 5.428
| createPost | Avg| 796ms| 775ms | -21ms | -2.639
| | P99| 4.632s| 4.83s | 198ms | 4.274
| createUser | Avg| 258ms| 264ms | 6ms | 2.326
| | P99| 1.893s| 2.001s | 108ms | 5.705
| deleteDraft | Avg| 12ms| 13ms | 1ms | 8.162
| | P99| 170ms| 201ms | 31ms | 18.228
| deletePost | Avg| 67ms| 39ms | -28ms | -41.990
| | P99| 445ms| 425ms | -20ms | -4.494
| followThreadByUser | Avg| 87ms| 40ms | -47ms | -53.786
| | P99| 479ms| 407ms | -72ms | -15.026
| getAllTeams | Avg| 7ms| 8ms | 1ms | 13.836
| | P99| 106ms| 142ms | 36ms | 33.995
| getAnalytics | Avg| 350ms| 70ms | -280ms | -79.927
| | P99| 990ms| 100ms | -890ms | -89.899
| getCategoriesForTeamForUser | Avg| 38ms| 26ms | -12ms | -31.432
| | P99| 233ms| 241ms | 8ms | 3.428
| getChannel | Avg| 19ms| 18ms | -1ms | -5.169
| | P99| 218ms| 264ms | 46ms | 21.053
| getChannelMember | Avg| 15ms| 14ms | -1ms | -6.488
| | P99| 214ms| 224ms | 10ms | 4.665
| getChannelMembers | Avg| 15ms| 6ms | -9ms | -58.235
| | P99| 96ms| 24ms | -72ms | -74.612
| getChannelMembersForTeamForUser | Avg| 11ms| 12ms | 1ms | 9.107
| | P99| 125ms| 166ms | 41ms | 32.738
| getChannelMembersForUser | Avg| 11ms| 9ms | -2ms | -18.433
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 99ms| 104ms | 5ms | 5.049
| getChannelUnread | Avg| 10ms| 6ms | -4ms | -42.068
| | P99| 116ms| 98ms | -18ms | -15.580
| getChannelsForTeamForUser | Avg| 10ms| 11ms | 1ms | 9.710
| | P99| 141ms| 176ms | 35ms | 24.876
| getChannelsForUser | Avg| 10ms| 8ms | -2ms | -20.994
| | P99| 134ms| 101ms | -33ms | -24.641
| getClientConfig | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 228ms| 237ms | 9ms | 3.943
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 12ms| 13ms | 1ms | 8.009
| | P99| 164ms| 188ms | 24ms | 14.590
| getFilePreview | Avg| 70ms| 71ms | 1ms | 1.438
| | P99| 402ms| 421ms | 19ms | 4.726
| getFileThumbnail | Avg| 51ms| 52ms | 1ms | 1.969
| | P99| 267ms| 371ms | 104ms | 39.013
| getFilteredUsersStats | Avg| 31ms| 0s | -31ms | -99.760
| | P99| 50ms| 0s | -50ms | -100.821
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 15ms| 26ms | 11ms | 73.564
| | P99| 125ms| 214ms | 89ms | 70.923
| getPostThread | Avg| 49ms| 54ms | 5ms | 10.300
| | P99| 463ms| 618ms | 155ms | 33.476
| getPostsForChannel | Avg| 92ms| 100ms | 8ms | 8.694
| | P99| 994ms| 1.431s | 437ms | 43.963
| getPostsForChannelAroundLastUnread | Avg| 36ms| 43ms | 7ms | 19.362
| | P99| 448ms| 585ms | 137ms | 30.595
| getPreferences | Avg| 7ms| 8ms | 1ms | 14.249
| | P99| 93ms| 130ms | 37ms | 39.827
| getPrevTrialLicense | Avg| 3ms| 18ms | 15ms | 579.798
| | P99| 10ms| 25ms | 15ms | 153.061
| getProductNotices | Avg| 1ms| 0s | -1ms | -71.858
| | P99| 5ms| 0s | -5ms | -100.952
| getProfileImage | Avg| 81ms| 76ms | -5ms | -6.152
| | P99| 463ms| 468ms | 5ms | 1.081
| getPublicChannelsForTeam | Avg| 32ms| 35ms | 3ms | 9.370
| | P99| 226ms| 253ms | 27ms | 11.957
| getRolesByNames | Avg| 7ms| 4ms | -3ms | -40.263
| | P99| 95ms| 25ms | -70ms | -73.684
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 11ms| 10ms | -1ms | -9.256
| | P99| 159ms| 183ms | 24ms | 15.115
| getTeamMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 126ms| 139ms | 13ms | 10.338
| getTeamStats | Avg| 74ms| 77ms | 3ms | 4.059
| | P99| 242ms| 243ms | 1ms | 0.414
| getTeamsForUser | Avg| 6ms| 7ms | 1ms | 17.188
| | P99| 88ms| 105ms | 17ms | 19.394
| getTeamsUnreadForUser | Avg| 12ms| 14ms | 2ms | 16.602
| | P99| 190ms| 220ms | 30ms | 15.799
| getThreadsForUser | Avg| 13ms| 14ms | 1ms | 7.817
| | P99| 162ms| 191ms | 29ms | 17.928
| getUser | Avg| 10ms| 12ms | 2ms | 19.511
| | P99| 204ms| 232ms | 28ms | 13.709
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 41ms| 45ms | 4ms | 9.769
| getUsers | Avg| 12ms| 13ms | 1ms | 8.594
| | P99| 203ms| 224ms | 21ms | 10.332
| getUsersByGroupChannelIds | Avg| 6ms| 0s | -6ms | -93.879
| | P99| 10ms| 0s | -10ms | -100.503
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 41ms | 2ms | 5.069
| getUsersByNames | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 142ms| 173ms | 31ms | 21.908
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 11ms| 12ms | 1ms | 9.343
| | P99| 48ms| 94ms | 46ms | 96.336
| login | Avg| 178ms| 99ms | -79ms | -44.469
| | P99| 1.708s| 842ms | -866ms | -50.694
| logout | Avg| 214ms| 111ms | -103ms | -48.138
| | P99| 2.185s| 473ms | -1.712s | -78.353
| patchPost | Avg| 110ms| 86ms | -24ms | -21.869
| | P99| 1.45s| 804ms | -646ms | -44.552
| removeUserCustomStatus | Avg| 373ms| 368ms | -5ms | -1.341
| | P99| 1.907s| 1.94s | 33ms | 1.730
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 289ms| 366ms | 77ms | 26.652
| searchAllChannels | Avg| 57ms| 61ms | 4ms | 6.992
| | P99| 237ms| 244ms | 7ms | 2.955
| searchGroupChannels | Avg| 19ms| 14ms | -5ms | -26.865
| | P99| 174ms| 187ms | 13ms | 7.492
| searchPostsInTeam | Avg| 314ms| 319ms | 5ms | 1.591
| | P99| 3.48s| 4.32s | 840ms | 24.137
| searchUsers | Avg| 56ms| 58ms | 2ms | 3.546
| | P99| 238ms| 243ms | 5ms | 2.105
| setPostReminder | Avg| 53ms| 57ms | 4ms | 7.516
| | P99| 461ms| 464ms | 3ms | 0.650
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 44ms| 56ms | 12ms | 27.369
| | P99| 392ms| 620ms | 228ms | 58.182
| updateCategoriesForTeamForUser | Avg| 203ms| 221ms | 18ms | 8.885
| | P99| 2.058s| 2.065s | 7ms | 0.340
| updateCategoryForTeamForUser | Avg| 194ms| 0s | -194ms | -100.068
| | P99| 249ms| 0s | -249ms | -100.201
| updatePreferences | Avg| 33ms| 38ms | 5ms | 15.305
| | P99| 363ms| 429ms | 66ms | 18.183
| updateReadStateAllThreadsByUser | Avg| 13ms| 9ms | -4ms | -30.221
| | P99| 25ms| 48ms | 23ms | 92.836
| updateReadStateThreadByUser | Avg| 113ms| 116ms | 3ms | 2.646
| | P99| 861ms| 945ms | 84ms | 9.754
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 455ms| 463ms | 8ms | 1.758
| | P99| 2.072s| 2.102s | 30ms | 1.448
| upsertDraft | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 184ms| 207ms | 23ms | 12.473
| viewChannel | Avg| 37ms| 38ms | 1ms | 2.683
| | P99| 419ms| 458ms | 39ms | 9.298
