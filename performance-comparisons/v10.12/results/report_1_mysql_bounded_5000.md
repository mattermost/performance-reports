### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 529ms | 527ms | 21280.14
| UserStore.GetProfilesInChannel | avg | 3ms | 7ms | 4ms | 150.31
| UserStore.GetMany | avg | 3ms | 5ms | 2ms | 76.38
| UserStore.IsEmpty | avg | 3ms | 5ms | 2ms | 63.19
| JobStore.GetNewestJobByStatusesAndType | avg | 3ms | 5ms | 2ms | 61.33
| SessionStore.GetLRUSessions | avg | 5ms | 8ms | 3ms | 57.55
| ChannelStore.GetGuestCount | avg | 6ms | 9ms | 3ms | 52.15
| PostStore.SearchPostsForUser | avg | 57ms | 86ms | 29ms | 50.95
| GroupStore.GetByName | avg | 6ms | 9ms | 3ms | 50.90
| UserStore.GetForLogin | avg | 6ms | 9ms | 3ms | 49.15
| ChannelStore.Get | avg | 4ms | 6ms | 2ms | 48.90
| StatusStore.Get | avg | 4ms | 6ms | 2ms | 47.63
| ThreadStore.GetTotalThreads | avg | 4ms | 6ms | 2ms | 45.95
| ChannelStore.GetMemberLastViewedAt | avg | 4ms | 6ms | 2ms | 45.76
| ThreadStore.GetTotalUnreadThreads | avg | 4ms | 6ms | 2ms | 45.73
| ChannelStore.GetMemberCount | avg | 89ms | 127ms | 38ms | 42.57
| TeamStore.GetAllPage | avg | 5ms | 7ms | 2ms | 40.18
| TeamStore.GetTeamsForUser | avg | 5ms | 7ms | 2ms | 40.15
| ScheduledPostStore.GetScheduledPostsForUser | avg | 5ms | 7ms | 2ms | 39.90
| TeamStore.GetChannelUnreadsForAllTeams | avg | 5ms | 7ms | 2ms | 39.74
| UserTermsOfServiceStore.GetByUser | avg | 5ms | 7ms | 2ms | 39.48
| TeamStore.GetTeamsByUserId | avg | 5ms | 7ms | 2ms | 38.66
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 10ms | 14ms | 4ms | 38.55
| ChannelStore.GetChannelsByUser | avg | 5ms | 7ms | 2ms | 37.32
| UserStore.GetAllProfilesInChannel | avg | 256ms | 347ms | 91ms | 35.55
| ChannelStore.GetMembersForUserWithPagination | avg | 6ms | 8ms | 2ms | 31.34
| PreferenceStore.GetAll | avg | 7ms | 9ms | 2ms | 30.53
| PostStore.GetPosts | avg | 8ms | 10ms | 2ms | 25.98
| SessionStore.Get | avg | 9ms | 11ms | 2ms | 22.98
| ChannelStore.SaveMember | avg | 41ms | 50ms | 9ms | 21.88
| SessionStore.Save | avg | 10ms | 12ms | 2ms | 19.67
| UserStore.Count | avg | 107ms | 124ms | 17ms | 15.94
| ChannelStore.CreateDirectChannel | avg | 24ms | 26ms | 2ms | 8.30
| UserStore.AutocompleteUsersInChannel | avg | 142ms | 150ms | 8ms | 5.64
| UserStore.AnalyticsActiveCount | avg | 121ms | 125ms | 4ms | 3.30
| UserStore.Search | avg | 62ms | 64ms | 2ms | 3.21
| ChannelStore.Autocomplete | avg | 981ms | 1.01s | 29ms | 2.96
| TeamStore.GetTotalMemberCount | avg | 76ms | 78ms | 2ms | 2.62
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 995ms | 990ms | 19996.99
| UserStore.GetMany | p99 | 5ms | 87ms | 82ms | 1656.57
| JobStore.GetNewestJobByStatusesAndType | p99 | 8ms | 51ms | 43ms | 573.33
| JobStore.GetCountByStatusAndType | p99 | 7ms | 44ms | 37ms | 513.89
| UserStore.GetProfilesInChannel | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.SearchPostsForUser | p99 | 405ms | 1.918s | 1.513s | 373.25
| ChannelStore.CreateDirectChannel | p99 | 50ms | 173ms | 123ms | 246.47
| EmojiStore.GetByName | p99 | 9ms | 29ms | 20ms | 233.39
| ChannelStore.GetPinnedPostCount | p99 | 10ms | 31ms | 21ms | 210.76
| PostAcknowledgementStore.GetForPost | p99 | 23ms | 61ms | 38ms | 163.80
| UserStore.GetAllProfilesInChannel | p99 | 972ms | 2.453s | 1.481s | 152.41
| SessionStore.GetLRUSessions | p99 | 50ms | 123ms | 73ms | 147.15
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 22ms | 13ms | 142.08
| ChannelStore.GetGuestCount | p99 | 64ms | 141ms | 77ms | 120.83
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 90ms | 195ms | 105ms | 116.62
| GroupStore.GetByName | p99 | 68ms | 145ms | 77ms | 112.42
| ChannelStore.GetMemberCount | p99 | 455ms | 956ms | 501ms | 110.03
| UserStore.IsEmpty | p99 | 41ms | 83ms | 42ms | 103.46
| TeamStore.Get | p99 | 16ms | 32ms | 16ms | 102.88
| StatusStore.UpdateExpiredDNDStatuses | p99 | 28ms | 56ms | 28ms | 100.90
| ChannelStore.Get | p99 | 45ms | 89ms | 44ms | 96.78
| StatusStore.SaveOrUpdateMany | p99 | 11ms | 22ms | 11ms | 95.66
| SessionStore.Save | p99 | 71ms | 135ms | 64ms | 90.63
| ChannelStore.GetMembersForUser | p99 | 25ms | 47ms | 22ms | 89.69
| StatusStore.Get | p99 | 43ms | 81ms | 38ms | 87.82
| ChannelStore.GetChannels | p99 | 26ms | 49ms | 23ms | 86.90
| ChannelStore.SaveMember | p99 | 237ms | 441ms | 204ms | 86.18
| PostStore.GetEtag | p99 | 44ms | 81ms | 37ms | 84.89
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 47ms | 87ms | 40ms | 84.69
| PropertyFieldStore.SearchPropertyFields | p99 | 48ms | 88ms | 40ms | 83.98
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 12ms | 22ms | 10ms | 82.58
| PostPersistentNotificationStore.GetSingle | p99 | 10ms | 18ms | 8ms | 81.73
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 48ms | 87ms | 39ms | 81.41
| ThreadStore.GetTeamsUnreadForUser | p99 | 49ms | 89ms | 40ms | 81.05
| UserStore.GetProfilesByUsernames | p99 | 9ms | 16ms | 7ms | 80.91
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateOptimistically | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetAllProfiles | p99 | 45ms | 81ms | 36ms | 80.38
| LinkMetadataStore.Get | p99 | 5ms | 9ms | 4ms | 80.13
| PostStore.GetSingle | p99 | 5ms | 9ms | 4ms | 80.05
| TeamStore.GetTeamsByUserId | p99 | 49ms | 88ms | 39ms | 79.97
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 49ms | 88ms | 39ms | 79.85
| TeamStore.GetAllPage | p99 | 49ms | 88ms | 39ms | 79.64
| TeamStore.GetTeamsForUser | p99 | 49ms | 88ms | 39ms | 79.49
| UserStore.GetForLogin | p99 | 74ms | 133ms | 59ms | 79.25
| ChannelStore.GetChannelsByUser | p99 | 48ms | 86ms | 38ms | 79.14
| ChannelStore.GetMemberLastViewedAt | p99 | 47ms | 84ms | 37ms | 78.22
| UserTermsOfServiceStore.GetByUser | p99 | 54ms | 96ms | 42ms | 77.88
| ChannelStore.GetMembersForUserWithPagination | p99 | 51ms | 90ms | 39ms | 76.21
| ChannelStore.SearchGroupChannels | p99 | 23ms | 40ms | 17ms | 73.63
| PostStore.GetPosts | p99 | 56ms | 96ms | 40ms | 71.98
| SharedChannelStore.HasChannel | p99 | 10ms | 17ms | 7ms | 71.86
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 46ms | 79ms | 33ms | 71.30
| FileInfoStore.Save | p99 | 10ms | 17ms | 7ms | 71.15
| PostStore.GetPostsBefore | p99 | 17ms | 29ms | 12ms | 70.18
| ThreadStore.GetTotalUnreadThreads | p99 | 46ms | 77ms | 31ms | 68.11
| TeamStore.GetMember | p99 | 28ms | 47ms | 19ms | 67.04
| ThreadStore.GetTotalThreads | p99 | 45ms | 75ms | 30ms | 66.29
| RoleStore.GetByNames | p99 | 5ms | 8ms | 3ms | 60.61
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 19ms | 7ms | 60.09
| ChannelStore.IsReadOnlyChannel | p99 | 7ms | 11ms | 4ms | 59.01
| ThreadStore.GetThreadsForUser | p99 | 17ms | 27ms | 10ms | 58.79
| PreferenceStore.Get | p99 | 14ms | 22ms | 8ms | 58.73
| ChannelStore.GetAllChannelMembersForUser | p99 | 24ms | 38ms | 14ms | 57.33
| ThreadStore.GetTotalUnreadMentions | p99 | 41ms | 64ms | 23ms | 55.64
| ThreadStore.GetMembershipForUser | p99 | 9ms | 14ms | 5ms | 55.53
| UserStore.GetUnreadCount | p99 | 21ms | 32ms | 11ms | 51.47
| GroupStore.GetGroups | p99 | 33ms | 50ms | 17ms | 51.16
| PreferenceStore.GetAll | p99 | 67ms | 99ms | 32ms | 48.11
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 13ms | 19ms | 6ms | 47.23
| ChannelStore.GetByName | p99 | 66ms | 95ms | 29ms | 43.95
| FileInfoStore.SetContent | p99 | 17ms | 24ms | 7ms | 41.42
| WebhookStore.GetOutgoingByTeam | p99 | 22ms | 31ms | 9ms | 40.21
| ThreadStore.GetThreadForUser | p99 | 19ms | 26ms | 7ms | 37.60
| ThreadStore.GetThreadFollowers | p99 | 16ms | 22ms | 6ms | 36.97
| ChannelStore.GetFileCount | p99 | 19ms | 26ms | 7ms | 36.13
| PostAcknowledgementStore.GetForPosts | p99 | 23ms | 31ms | 8ms | 34.54
| PostPriorityStore.GetForPosts | p99 | 24ms | 32ms | 8ms | 33.99
| SessionStore.Get | p99 | 74ms | 99ms | 25ms | 33.62
| UserStore.Count | p99 | 416ms | 540ms | 124ms | 29.79
| ReactionStore.GetForPost | p99 | 10ms | 13ms | 3ms | 28.60
| ChannelStore.GetMemberForPost | p99 | 8ms | 10ms | 2ms | 24.23
| PostStore.GetPostsSince | p99 | 46ms | 57ms | 11ms | 23.79
| UserStore.AutocompleteUsersInChannel | p99 | 456ms | 542ms | 86ms | 18.88
| ChannelStore.CreateInitialSidebarCategories | p99 | 80ms | 89ms | 9ms | 11.30
| PostStore.Get | p99 | 19ms | 21ms | 2ms | 10.75
| TeamStore.SaveMember | p99 | 228ms | 236ms | 8ms | 3.51
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetAllByTypePage | avg | 3ms | 0s | -3ms | -118.53
| ChannelStore.GetByNameIncludeDeleted | avg | 3ms | 0s | -3ms | -118.07
| SchemeStore.GetAllPage | avg | 3ms | 0s | -3ms | -116.24
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -116.13
| ChannelStore.GetMembers | avg | 4ms | 0s | -4ms | -112.30
| ChannelStore.CreateSidebarCategory | avg | 23ms | 0s | -23ms | -101.50
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 4ms | 2ms | -2ms | -47.40
| PluginStore.List | avg | 5ms | 3ms | -2ms | -43.86
| BotStore.Get | avg | 7ms | 5ms | -2ms | -28.06
| ChannelStore.AutocompleteInTeamForSearch | avg | 319ms | 263ms | -56ms | -17.53
| ChannelBookmarkStore.Save | avg | 13ms | 11ms | -2ms | -15.02
| ChannelStore.GetTeamChannels | avg | 34ms | 31ms | -3ms | -8.94
| PostStore.AnalyticsPostCountByTeam | avg | 514ms | 493ms | -21ms | -4.08
| ChannelStore.AnalyticsCountAll | avg | 148ms | 142ms | -6ms | -4.05
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -100.95
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| PluginStore.List | p99 | 82ms | 5ms | -77ms | -93.91
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 46ms | 5ms | -41ms | -89.62
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 47ms | 10ms | -37ms | -78.31
| UserStore.Update | p99 | 35ms | 10ms | -25ms | -72.46
| ScheduledPostStore.CreateScheduledPost | p99 | 10ms | 5ms | -5ms | -51.81
| BotStore.Get | p99 | 91ms | 45ms | -46ms | -50.55
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -46.78
| UserAccessTokenStore.GetByToken | p99 | 9ms | 5ms | -4ms | -42.55
| PreferenceStore.DeleteCategoryAndName | p99 | 9ms | 5ms | -4ms | -42.33
| UserStore.GetByUsername | p99 | 75ms | 54ms | -21ms | -27.91
| FileInfoStore.AttachToPost | p99 | 21ms | 16ms | -5ms | -24.13
| ProductNoticesStore.View | p99 | 155ms | 130ms | -25ms | -16.10
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 92ms | 79ms | -13ms | -14.08
| UserStore.UpdateFailedPasswordAttempts | p99 | 28ms | 25ms | -3ms | -10.80
| ChannelStore.Save | p99 | 74ms | 67ms | -7ms | -9.46
| PostPriorityStore.GetForPost | p99 | 24ms | 22ms | -2ms | -8.40
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.451s | 2.359s | -92ms | -3.75
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 64ms | 93ms | 29ms | 45.56
| getChannelStats | avg | 7ms | 10ms | 3ms | 40.30
| getTeamsForUser | avg | 5ms | 7ms | 2ms | 38.15
| listCPAFields | avg | 5ms | 7ms | 2ms | 38.13
| getTeamMembersForUser | avg | 5ms | 7ms | 2ms | 36.59
| getChannelsForUser | avg | 5ms | 7ms | 2ms | 36.53
| getCategoriesForTeamForUser | avg | 11ms | 15ms | 4ms | 35.67
| getUser | avg | 6ms | 8ms | 2ms | 34.00
| getTeamsUnreadForUser | avg | 9ms | 12ms | 3ms | 32.33
| getChannelMembersForUser | avg | 6ms | 8ms | 2ms | 30.98
| getPostsForChannelAroundLastUnread | avg | 33ms | 43ms | 10ms | 30.76
| getChannel | avg | 7ms | 9ms | 2ms | 29.98
| getPreferences | avg | 7ms | 9ms | 2ms | 29.96
| getTeamScheduledPosts | avg | 10ms | 13ms | 3ms | 29.32
| addTeamMember | avg | 892ms | 1.094s | 202ms | 22.65
| saveReaction | avg | 10ms | 12ms | 2ms | 19.86
| createUser | avg | 333ms | 371ms | 38ms | 11.41
| createPost | avg | 153ms | 168ms | 15ms | 9.80
| getPostsForChannel | avg | 23ms | 25ms | 2ms | 8.59
| login | avg | 77ms | 83ms | 6ms | 7.79
| autocompleteUsers | avg | 117ms | 125ms | 8ms | 6.85
| createGroupChannel | avg | 231ms | 240ms | 9ms | 3.90
| searchUsers | avg | 63ms | 65ms | 2ms | 3.17
| searchAllChannels | avg | 981ms | 1.01s | 29ms | 2.96
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | p99 | 10ms | 112ms | 102ms | 1020.05
| searchPostsInTeam | p99 | 449ms | 1.918s | 1.469s | 327.14
| addTeamMember | p99 | 2.447s | 6.269s | 3.822s | 156.19
| getCategoriesForTeamForUser | p99 | 92ms | 198ms | 106ms | 115.22
| getTeamScheduledPosts | p99 | 96ms | 195ms | 99ms | 103.29
| createUser | p99 | 958ms | 1.941s | 983ms | 102.60
| getPostsForChannelAroundLastUnread | p99 | 231ms | 453ms | 222ms | 96.20
| getTeamsUnreadForUser | p99 | 90ms | 175ms | 85ms | 94.09
| saveReaction | p99 | 44ms | 84ms | 40ms | 90.52
| getChannelMembersForTeamForUser | p99 | 25ms | 47ms | 22ms | 89.38
| listCPAFields | p99 | 49ms | 91ms | 42ms | 85.44
| getChannelsForUser | p99 | 48ms | 87ms | 39ms | 80.61
| getTeamsForUser | p99 | 49ms | 88ms | 39ms | 79.92
| getChannelsForTeamForUser | p99 | 27ms | 48ms | 21ms | 79.20
| getChannelMembersForUser | p99 | 51ms | 90ms | 39ms | 76.11
| getUsersByNames | p99 | 9ms | 16ms | 7ms | 74.58
| searchGroupChannels | p99 | 23ms | 40ms | 17ms | 73.63
| getTeamMembersForUser | p99 | 54ms | 90ms | 36ms | 66.74
| getAllTeams | p99 | 56ms | 92ms | 36ms | 64.80
| getUsers | p99 | 45ms | 74ms | 29ms | 64.26
| viewChannel | p99 | 49ms | 79ms | 30ms | 61.06
| getChannelMember | p99 | 90ms | 144ms | 54ms | 60.02
| getThreadsForUser | p99 | 43ms | 67ms | 24ms | 55.66
| createPost | p99 | 905ms | 1.35s | 445ms | 49.17
| getPreferences | p99 | 67ms | 99ms | 32ms | 47.64
| getUser | p99 | 66ms | 97ms | 31ms | 46.65
| createGroupChannel | p99 | 491ms | 700ms | 209ms | 42.57
| getClientConfig | p99 | 50ms | 70ms | 20ms | 39.77
| listChannelBookmarksForChannel | p99 | 16ms | 22ms | 6ms | 36.72
| getTeamMember | p99 | 6ms | 8ms | 2ms | 36.23
| login | p99 | 412ms | 473ms | 61ms | 14.80
| getChannelStats | p99 | 222ms | 249ms | 27ms | 12.15
| autocompleteUsers | p99 | 435ms | 487ms | 52ms | 11.95
| getPostsForChannel | p99 | 194ms | 217ms | 23ms | 11.87
| createDirectChannel | p99 | 248ms | 268ms | 20ms | 8.05
| getProfileImage | p99 | 469ms | 488ms | 19ms | 4.05
| searchUsers | p99 | 246ms | 249ms | 3ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | avg | 2ms | 0s | -2ms | -126.68
| getJobsByType | avg | 3ms | 0s | -3ms | -113.83
| getChannelMembers | avg | 4ms | 0s | -4ms | -102.67
| createCategoryForTeamForUser | avg | 26ms | 0s | -26ms | -100.36
| getRolesByNames | avg | 3ms | 1ms | -2ms | -78.64
| autocompleteChannelsForTeamForSearch | avg | 319ms | 263ms | -56ms | -17.53
| createChannel | avg | 203ms | 179ms | -24ms | -11.83
| addChannelMember | avg | 167ms | 153ms | -14ms | -8.36
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getJobsByType | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| getChannelUnread | p99 | 10ms | 5ms | -5ms | -52.63
| patchPost | p99 | 58ms | 50ms | -8ms | -13.70
| autocompleteChannelsForTeamForSearch | p99 | 2.451s | 2.359s | -92ms | -3.75
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 7ms| 5ms | -2ms | -28.062
| |  P99| 91ms| 45ms | -46ms | -50.549
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 19ms | 6ms | 47.229
| ChannelBookmarkStore.Save |  Avg| 13ms| 11ms | -2ms | -15.015
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 148ms| 142ms | -6ms | -4.053
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 981ms| 1.01s | 29ms | 2.957
| |  P99| 2.493s| 2.494s | 1ms | 0.040
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 319ms| 263ms | -56ms | -17.534
| |  P99| 2.451s| 2.359s | -92ms | -3.754
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 26ms | 2ms | 8.298
| |  P99| 50ms| 173ms | 123ms | 246.468
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 80ms| 89ms | 9ms | 11.297
| ChannelStore.CreateSidebarCategory |  Avg| 23ms| 0s | -23ms | -101.497
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 4ms| 6ms | 2ms | 48.897
| |  P99| 45ms| 89ms | 44ms | 96.782
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 4ms | 1ms | 28.643
| |  P99| 24ms| 38ms | 14ms | 57.328
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 17ms| 16ms | -1ms | -5.985
| |  P99| 92ms| 79ms | -13ms | -14.082
| ChannelStore.GetByName |  Avg| 7ms| 8ms | 1ms | 15.110
| |  P99| 66ms| 95ms | 29ms | 43.949
| ChannelStore.GetByNameIncludeDeleted |  Avg| 3ms| 0s | -3ms | -118.065
| |  P99| 5ms| 0s | -5ms | -100.949
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -38.957
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 49ms | 23ms | 86.904
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 7ms | 2ms | 37.324
| |  P99| 48ms| 86ms | 38ms | 79.137
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 22ms | 10ms | 82.584
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 26ms | 7ms | 36.125
| ChannelStore.GetGuestCount |  Avg| 6ms| 9ms | 3ms | 52.151
| |  P99| 64ms| 141ms | 77ms | 120.829
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 89ms| 127ms | 38ms | 42.568
| |  P99| 455ms| 956ms | 501ms | 110.026
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.229
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 6ms | 2ms | 45.758
| |  P99| 47ms| 84ms | 37ms | 78.219
| ChannelStore.GetMembers |  Avg| 4ms| 0s | -4ms | -112.299
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 47ms | 22ms | 89.689
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 9ms| 8ms | -1ms | -10.596
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 8ms | 2ms | 31.342
| |  P99| 51ms| 90ms | 39ms | 76.214
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 31ms | 21ms | 210.760
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.385
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 10ms| 14ms | 4ms | 38.551
| |  P99| 90ms| 195ms | 105ms | 116.620
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 4ms | -1ms | -21.640
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 34ms| 31ms | -3ms | -8.942
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 11ms | 4ms | 59.006
| ChannelStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 74ms| 67ms | -7ms | -9.460
| ChannelStore.SaveMember |  Avg| 41ms| 50ms | 9ms | 21.885
| |  P99| 237ms| 441ms | 204ms | 86.183
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 28.611
| |  P99| 23ms| 40ms | 17ms | 73.634
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 31ms | -1ms | -3.167
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 19ms | 7ms | 60.086
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 9ms| 8ms | -1ms | -10.549
| |  P99| 47ms| 10ms | -37ms | -78.306
| DraftStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.391
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 29ms | 20ms | 233.392
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -15.294
| |  P99| 21ms| 16ms | -5ms | -24.135
| FileInfoStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.167
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 71.155
| FileInfoStore.SetContent |  Avg| 8ms| 9ms | 1ms | 11.983
| |  P99| 17ms| 24ms | 7ms | 41.418
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 6ms | 1ms | 21.574
| |  P99| 47ms| 87ms | 40ms | 84.693
| GroupStore.GetByName |  Avg| 6ms| 9ms | 3ms | 50.904
| |  P99| 68ms| 145ms | 77ms | 112.421
| GroupStore.GetGroups |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 50ms | 17ms | 51.160
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.446
| JobStore.GetAllByTypePage |  Avg| 3ms| 0s | -3ms | -118.532
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 4ms | 1ms | 37.145
| |  P99| 7ms| 44ms | 37ms | 513.889
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 5ms | 2ms | 61.330
| |  P99| 8ms| 51ms | 43ms | 573.333
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.204
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 9ms | 1ms | 11.874
| |  P99| 22ms| 23ms | 1ms | 4.592
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.133
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.List |  Avg| 5ms| 3ms | -2ms | -43.865
| |  P99| 82ms| 5ms | -77ms | -93.912
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 32.729
| |  P99| 23ms| 61ms | 38ms | 163.798
| PostAcknowledgementStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 31ms | 8ms | 34.537
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 81.733
| PostPriorityStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.404
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 32ms | 8ms | 33.993
| PostStore.AnalyticsPostCount |  Avg| 2ms| 529ms | 527ms | 21280.144
| |  P99| 5ms| 995ms | 990ms | 19996.985
| PostStore.AnalyticsPostCountByTeam |  Avg| 514ms| 493ms | -21ms | -4.085
| |  P99| 995ms| 990ms | -5ms | -0.503
| PostStore.Delete |  Avg| 17ms| 18ms | 1ms | 5.869
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.753
| PostStore.GetEtag |  Avg| 4ms| 5ms | 1ms | 24.144
| |  P99| 44ms| 81ms | 37ms | 84.888
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 8ms| 10ms | 2ms | 25.981
| |  P99| 56ms| 96ms | 40ms | 71.981
| PostStore.GetPostsAfter |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 4ms| 5ms | 1ms | 24.317
| |  P99| 17ms| 29ms | 12ms | 70.176
| PostStore.GetPostsByThread |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 57ms | 11ms | 23.786
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.051
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 57ms| 86ms | 29ms | 50.950
| |  P99| 405ms| 1.918s | 1.513s | 373.247
| PostStore.SetPostReminder |  Avg| 9ms| 8ms | -1ms | -11.152
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 16ms| 15ms | -1ms | -6.408
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -37.483
| |  P99| 9ms| 5ms | -4ms | -42.328
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 22ms | 8ms | 58.730
| PreferenceStore.GetAll |  Avg| 7ms| 9ms | 2ms | 30.535
| |  P99| 67ms| 99ms | 32ms | 48.109
| PreferenceStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 59ms| 60ms | 1ms | 1.707
| ProductNoticesStore.GetViews |  Avg| 2ms| 3ms | 1ms | 42.143
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 36ms| 35ms | -1ms | -2.807
| |  P99| 155ms| 130ms | -25ms | -16.095
| PropertyFieldStore.SearchPropertyFields |  Avg| 5ms| 6ms | 1ms | 20.867
| |  P99| 48ms| 88ms | 40ms | 83.984
| PropertyValueStore.SearchPropertyValues |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.195
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 28.598
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -116.132
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -78.557
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.813
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 22ms | 13ms | 142.077
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 5ms| 7ms | 2ms | 39.905
| |  P99| 49ms| 88ms | 39ms | 79.852
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 4ms| 2ms | -2ms | -47.399
| |  P99| 46ms| 5ms | -41ms | -89.617
| SchemeStore.GetAllPage |  Avg| 3ms| 0s | -3ms | -116.243
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 9ms| 11ms | 2ms | 22.979
| |  P99| 74ms| 99ms | 25ms | 33.622
| SessionStore.GetLRUSessions |  Avg| 5ms| 8ms | 3ms | 57.551
| |  P99| 50ms| 123ms | 73ms | 147.153
| SessionStore.GetSessionsExpired |  Avg| 2ms| 3ms | 1ms | 44.095
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.534
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 10ms| 12ms | 2ms | 19.667
| |  P99| 71ms| 135ms | 64ms | 90.628
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 71.860
| StatusStore.Get |  Avg| 4ms| 6ms | 2ms | 47.634
| |  P99| 43ms| 81ms | 38ms | 87.822
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 6.898
| StatusStore.SaveOrUpdateMany |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 11ms| 22ms | 11ms | 95.660
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 28ms| 56ms | 28ms | 100.901
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.813
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 32ms | 16ms | 102.882
| TeamStore.GetActiveMemberCount |  Avg| 99ms| 99ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 5ms| 7ms | 2ms | 40.177
| |  P99| 49ms| 88ms | 39ms | 79.642
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 7ms | 2ms | 39.735
| |  P99| 48ms| 87ms | 39ms | 81.408
| TeamStore.GetMember |  Avg| 3ms| 4ms | 1ms | 29.069
| |  P99| 28ms| 47ms | 19ms | 67.036
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 7ms | 2ms | 38.660
| |  P99| 49ms| 88ms | 39ms | 79.965
| TeamStore.GetTeamsForUser |  Avg| 5ms| 7ms | 2ms | 40.146
| |  P99| 49ms| 88ms | 39ms | 79.485
| TeamStore.GetTotalMemberCount |  Avg| 76ms| 78ms | 2ms | 2.624
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 77ms| 78ms | 1ms | 1.306
| |  P99| 228ms| 236ms | 8ms | 3.509
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 14ms | 5ms | 55.535
| ThreadStore.GetTeamsUnreadForUser |  Avg| 6ms| 7ms | 1ms | 17.924
| |  P99| 49ms| 89ms | 40ms | 81.051
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 22ms | 6ms | 36.970
| ThreadStore.GetThreadForUser |  Avg| 5ms| 6ms | 1ms | 19.612
| |  P99| 19ms| 26ms | 7ms | 37.602
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.609
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 4ms | 1ms | 29.289
| |  P99| 17ms| 27ms | 10ms | 58.788
| ThreadStore.GetTotalThreads |  Avg| 4ms| 6ms | 2ms | 45.945
| |  P99| 45ms| 75ms | 30ms | 66.293
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 5ms | 1ms | 24.983
| |  P99| 41ms| 64ms | 23ms | 55.636
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 6ms | 2ms | 45.733
| |  P99| 46ms| 77ms | 31ms | 68.106
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 5ms| 6ms | 1ms | 22.219
| |  P99| 46ms| 79ms | 33ms | 71.298
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.783
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.593
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.402
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 3ms| 2ms | -1ms | -33.619
| |  P99| 9ms| 5ms | -4ms | -42.546
| UserStore.AnalyticsActiveCount |  Avg| 121ms| 125ms | 4ms | 3.297
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 142ms| 150ms | 8ms | 5.639
| |  P99| 456ms| 542ms | 86ms | 18.879
| UserStore.Count |  Avg| 107ms| 124ms | 17ms | 15.937
| |  P99| 416ms| 540ms | 124ms | 29.789
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.744
| UserStore.GetAllProfiles |  Avg| 5ms| 6ms | 1ms | 20.067
| |  P99| 45ms| 81ms | 36ms | 80.381
| UserStore.GetAllProfilesInChannel |  Avg| 256ms| 347ms | 91ms | 35.550
| |  P99| 972ms| 2.453s | 1.481s | 152.411
| UserStore.GetByUsername |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 75ms| 54ms | -21ms | -27.907
| UserStore.GetForLogin |  Avg| 6ms| 9ms | 3ms | 49.155
| |  P99| 74ms| 133ms | 59ms | 79.252
| UserStore.GetMany |  Avg| 3ms| 5ms | 2ms | 76.377
| |  P99| 5ms| 87ms | 82ms | 1656.566
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 16ms | 7ms | 80.906
| UserStore.GetProfilesInChannel |  Avg| 3ms| 7ms | 4ms | 150.314
| |  P99| 5ms| 24ms | 19ms | 383.838
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 32ms | 11ms | 51.467
| UserStore.IsEmpty |  Avg| 3ms| 5ms | 2ms | 63.186
| |  P99| 41ms| 83ms | 42ms | 103.456
| UserStore.Save |  Avg| 72ms| 72ms | 0s | 0.000
| |  P99| 210ms| 210ms | 0s | 0.000
| UserStore.Search |  Avg| 62ms| 64ms | 2ms | 3.209
| |  P99| 246ms| 248ms | 2ms | 0.813
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 35ms| 10ms | -25ms | -72.462
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.805
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.158
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 7ms | 2ms | 39.478
| |  P99| 54ms| 96ms | 42ms | 77.878
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 31ms | 9ms | 40.211
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 167ms| 153ms | -14ms | -8.362
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 892ms| 1.094s | 202ms | 22.646
| | P99| 2.447s| 6.269s | 3.822s | 156.185
| autocompleteChannelsForTeamForSearch | Avg| 319ms| 263ms | -56ms | -17.531
| | P99| 2.451s| 2.359s | -92ms | -3.754
| autocompleteUsers | Avg| 117ms| 125ms | 8ms | 6.851
| | P99| 435ms| 487ms | 52ms | 11.954
| createCategoryForTeamForUser | Avg| 26ms| 0s | -26ms | -100.360
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 203ms| 179ms | -24ms | -11.827
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 18ms| 17ms | -1ms | -5.428
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 145ms| 146ms | 1ms | 0.689
| | P99| 248ms| 268ms | 20ms | 8.054
| createGroupChannel | Avg| 231ms| 240ms | 9ms | 3.903
| | P99| 491ms| 700ms | 209ms | 42.570
| createPost | Avg| 153ms| 168ms | 15ms | 9.795
| | P99| 905ms| 1.35s | 445ms | 49.171
| createSchedulePost | Avg| 5ms| 4ms | -1ms | -21.304
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 333ms| 371ms | 38ms | 11.405
| | P99| 958ms| 1.941s | 983ms | 102.600
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.691
| deletePost | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| followThreadByUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 6ms| 7ms | 1ms | 17.794
| | P99| 56ms| 92ms | 36ms | 64.803
| getCategoriesForTeamForUser | Avg| 11ms| 15ms | 4ms | 35.669
| | P99| 92ms| 198ms | 106ms | 115.221
| getChannel | Avg| 7ms| 9ms | 2ms | 29.982
| | P99| 10ms| 112ms | 102ms | 1020.052
| getChannelMember | Avg| 10ms| 11ms | 1ms | 10.353
| | P99| 90ms| 144ms | 54ms | 60.016
| getChannelMembers | Avg| 4ms| 0s | -4ms | -102.666
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 47ms | 22ms | 89.383
| getChannelMembersForUser | Avg| 6ms| 8ms | 2ms | 30.985
| | P99| 51ms| 90ms | 39ms | 76.111
| getChannelStats | Avg| 7ms| 10ms | 3ms | 40.302
| | P99| 222ms| 249ms | 27ms | 12.146
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -52.631
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 27ms| 48ms | 21ms | 79.196
| getChannelsForUser | Avg| 5ms| 7ms | 2ms | 36.532
| | P99| 48ms| 87ms | 39ms | 80.605
| getClientConfig | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 50ms| 70ms | 20ms | 39.772
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getFilePreview | Avg| 41ms| 41ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| getFileThumbnail | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| getJobsByType | Avg| 3ms| 0s | -3ms | -113.827
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 23ms| 25ms | 2ms | 8.594
| | P99| 194ms| 217ms | 23ms | 11.872
| getPostsForChannelAroundLastUnread | Avg| 33ms| 43ms | 10ms | 30.756
| | P99| 231ms| 453ms | 222ms | 96.201
| getPreferences | Avg| 7ms| 9ms | 2ms | 29.955
| | P99| 67ms| 99ms | 32ms | 47.639
| getPrevTrialLicense | Avg| 2ms| 0s | -2ms | -126.679
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 103ms| 104ms | 1ms | 0.973
| | P99| 469ms| 488ms | 19ms | 4.048
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getRolesByNames | Avg| 3ms| 1ms | -2ms | -78.641
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 6ms| 8ms | 2ms | 36.233
| getTeamMembersForUser | Avg| 5ms| 7ms | 2ms | 36.592
| | P99| 54ms| 90ms | 36ms | 66.736
| getTeamScheduledPosts | Avg| 10ms| 13ms | 3ms | 29.316
| | P99| 96ms| 195ms | 99ms | 103.289
| getTeamStats | Avg| 99ms| 99ms | 0s | 0.000
| | P99| 100ms| 100ms | 0s | 0.000
| getTeamsForUser | Avg| 5ms| 7ms | 2ms | 38.151
| | P99| 49ms| 88ms | 39ms | 79.921
| getTeamsUnreadForUser | Avg| 9ms| 12ms | 3ms | 32.333
| | P99| 90ms| 175ms | 85ms | 94.087
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 43ms| 67ms | 24ms | 55.659
| getUser | Avg| 6ms| 8ms | 2ms | 33.997
| | P99| 66ms| 97ms | 31ms | 46.647
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 6ms | 1ms | 19.748
| | P99| 45ms| 74ms | 29ms | 64.264
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 4ms | 1ms | 30.845
| | P99| 9ms| 16ms | 7ms | 74.579
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 5ms| 7ms | 2ms | 38.126
| | P99| 49ms| 91ms | 42ms | 85.444
| listCPAValues | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.893
| listChannelBookmarksForChannel | Avg| 3ms| 4ms | 1ms | 30.981
| | P99| 16ms| 22ms | 6ms | 36.722
| login | Avg| 77ms| 83ms | 6ms | 7.790
| | P99| 412ms| 473ms | 61ms | 14.797
| logout | Avg| 21ms| 22ms | 1ms | 4.781
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 58ms| 50ms | -8ms | -13.702
| removeUserCustomStatus | Avg| 87ms| 88ms | 1ms | 1.144
| | P99| 245ms| 246ms | 1ms | 0.409
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 12ms | 2ms | 19.864
| | P99| 44ms| 84ms | 40ms | 90.525
| searchAllChannels | Avg| 981ms| 1.01s | 29ms | 2.957
| | P99| 2.493s| 2.494s | 1ms | 0.040
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 40ms | 17ms | 73.634
| searchPostsInTeam | Avg| 64ms| 93ms | 29ms | 45.556
| | P99| 449ms| 1.918s | 1.469s | 327.141
| searchUsers | Avg| 63ms| 65ms | 2ms | 3.165
| | P99| 246ms| 249ms | 3ms | 1.219
| setPostReminder | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 44ms| 43ms | -1ms | -2.282
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 11ms| 10ms | -1ms | -9.404
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 477ms| 480ms | 3ms | 0.629
| | P99| 1s| 998ms | -2ms | -0.200
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 16ms| 16ms | 0s | 0.000
| viewChannel | Avg| 16ms| 17ms | 1ms | 6.344
| | P99| 49ms| 79ms | 30ms | 61.056
