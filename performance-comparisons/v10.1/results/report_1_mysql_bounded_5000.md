### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 633ms | 631ms | 26913.35
| ComplianceStore.MessageExport | avg | 3ms | 6ms | 3ms | 110.14
| ChannelStore.UpdateSidebarCategories | avg | 32ms | 59ms | 27ms | 83.10
| BotStore.Get | avg | 4ms | 6ms | 2ms | 48.00
| ChannelStore.AutocompleteInTeamForSearch | avg | 126ms | 132ms | 6ms | 4.75
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 2.47s | 2.465s | 49762.44
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 43ms | 38ms | 767.68
| JobStore.UpdateStatus | p99 | 9ms | 77ms | 68ms | 719.28
| ComplianceStore.MessageExport | p99 | 7ms | 47ms | 40ms | 553.63
| JobStore.UpdateOptimistically | p99 | 8ms | 35ms | 27ms | 318.30
| ChannelStore.UpdateSidebarCategories | p99 | 95ms | 238ms | 143ms | 151.32
| BotStore.Get | p99 | 46ms | 92ms | 46ms | 100.55
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 18ms | 9ms | 97.05
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 56ms | 87ms | 31ms | 55.60
| UserStore.Get | p99 | 5ms | 7ms | 2ms | 40.01
| ChannelStore.SearchGroupChannels | p99 | 39ms | 53ms | 14ms | 35.83
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 142ms | 165ms | 23ms | 16.20
| ChannelStore.AutocompleteInTeamForSearch | p99 | 674ms | 736ms | 62ms | 9.19
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -127.86
| ChannelStore.GetMembers | avg | 4ms | 0s | -4ms | -106.94
| UserStore.GetProfilesNotInChannel | avg | 6ms | 0s | -6ms | -105.50
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -100.66
| ChannelStore.GetTeamChannels | avg | 45ms | 0s | -45ms | -99.96
| SessionStore.GetSessionsExpired | avg | 13ms | 2ms | -11ms | -85.52
| ChannelStore.GetChannelsByUser | avg | 28ms | 6ms | -22ms | -79.33
| JobStore.GetCountByStatusAndType | avg | 9ms | 2ms | -7ms | -74.66
| JobStore.GetNewestJobByStatusesAndType | avg | 10ms | 3ms | -7ms | -73.48
| UserTermsOfServiceStore.GetByUser | avg | 10ms | 4ms | -6ms | -62.84
| TeamStore.GetTeamsByUserId | avg | 10ms | 4ms | -6ms | -61.76
| TeamStore.GetChannelUnreadsForAllTeams | avg | 9ms | 4ms | -5ms | -57.39
| ChannelStore.Get | avg | 9ms | 4ms | -5ms | -55.57
| TeamStore.GetAllPage | avg | 9ms | 4ms | -5ms | -55.41
| PreferenceStore.GetAll | avg | 13ms | 6ms | -7ms | -53.78
| EmojiStore.GetByName | avg | 4ms | 2ms | -2ms | -52.81
| BotStore.Save | avg | 8ms | 4ms | -4ms | -52.80
| ChannelStore.GetGuestCount | avg | 11ms | 5ms | -6ms | -52.43
| GroupStore.GetByName | avg | 10ms | 5ms | -5ms | -52.27
| UserStore.GetForLogin | avg | 10ms | 5ms | -5ms | -49.90
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 28ms | 14ms | -14ms | -49.80
| ChannelStore.GetMemberLastViewedAt | avg | 8ms | 4ms | -4ms | -49.00
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 8ms | 4ms | -4ms | -48.77
| TeamStore.GetTeamsForUser | avg | 8ms | 4ms | -4ms | -48.33
| DraftStore.GetDraftsForUser | avg | 6ms | 3ms | -3ms | -47.95
| JobStore.Get | avg | 4ms | 2ms | -2ms | -45.88
| UserAccessTokenStore.GetByToken | avg | 4ms | 2ms | -2ms | -45.54
| ThreadStore.GetTeamsUnreadForUser | avg | 9ms | 5ms | -4ms | -44.80
| SessionStore.GetLRUSessions | avg | 9ms | 5ms | -4ms | -44.78
| ThreadStore.GetTotalUnreadMentions | avg | 7ms | 4ms | -3ms | -44.04
| StatusStore.Get | avg | 7ms | 4ms | -3ms | -43.56
| ThreadStore.GetTotalUnreadThreads | avg | 7ms | 4ms | -3ms | -42.87
| ThreadStore.GetTotalThreads | avg | 7ms | 4ms | -3ms | -42.44
| PluginStore.List | avg | 5ms | 3ms | -2ms | -41.88
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 7ms | 4ms | -3ms | -41.66
| ThreadStore.GetThreadsForUser | avg | 5ms | 3ms | -2ms | -41.53
| PostStore.GetEtag | avg | 7ms | 4ms | -3ms | -40.79
| PostPriorityStore.GetForPosts | avg | 5ms | 3ms | -2ms | -37.61
| UserStore.IsEmpty | avg | 5ms | 3ms | -2ms | -37.35
| GroupStore.GetGroups | avg | 5ms | 3ms | -2ms | -37.26
| PostStore.GetPosts | avg | 11ms | 7ms | -4ms | -35.99
| UserStore.GetAllProfiles | avg | 8ms | 5ms | -3ms | -35.75
| ChannelStore.CreateDirectChannel | avg | 31ms | 20ms | -11ms | -35.61
| PostStore.GetPostsBefore | avg | 6ms | 4ms | -2ms | -35.22
| SessionStore.Get | avg | 11ms | 7ms | -4ms | -35.15
| ChannelStore.GetByName | avg | 9ms | 6ms | -3ms | -34.39
| ChannelStore.GetSidebarCategory | avg | 9ms | 6ms | -3ms | -33.45
| ChannelStore.CreateSidebarCategory | avg | 27ms | 18ms | -9ms | -33.41
| ChannelStore.GetMembersForUser | avg | 6ms | 4ms | -2ms | -33.15
| ChannelStore.GetChannels | avg | 6ms | 4ms | -2ms | -32.98
| FileInfoStore.GetByIds | avg | 6ms | 4ms | -2ms | -31.40
| SessionStore.Save | avg | 13ms | 9ms | -4ms | -30.87
| ChannelStore.SaveMember | avg | 54ms | 38ms | -16ms | -29.56
| StatusStore.UpdateExpiredDNDStatuses | avg | 8ms | 6ms | -2ms | -26.01
| ChannelStore.CreateInitialSidebarCategories | avg | 26ms | 21ms | -5ms | -19.10
| ChannelStore.GetPublicChannelsForTeam | avg | 16ms | 13ms | -3ms | -18.78
| PostStore.GetPostsSince | avg | 11ms | 9ms | -2ms | -18.65
| ChannelStore.GetMemberCount | avg | 172ms | 141ms | -31ms | -18.03
| PostStore.SearchPostsForUser | avg | 59ms | 50ms | -9ms | -15.32
| UserStore.Count | avg | 93ms | 82ms | -11ms | -11.78
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 19ms | 17ms | -2ms | -10.78
| UserStore.GetAllProfilesInChannel | avg | 475ms | 448ms | -27ms | -5.68
| TeamStore.SaveMember | avg | 103ms | 98ms | -5ms | -4.84
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 279ms | 271ms | -8ms | -2.87
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.92
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 0s | -10ms | -100.50
| ChannelStore.GetTeamChannels | p99 | 50ms | 0s | -50ms | -100.50
| JobStore.GetNewestJobByStatusesAndType | p99 | 220ms | 5ms | -215ms | -97.73
| JobStore.GetCountByStatusAndType | p99 | 209ms | 5ms | -204ms | -97.72
| ChannelStore.CreateDirectChannel | p99 | 510ms | 26ms | -484ms | -94.92
| SessionStore.GetSessionsExpired | p99 | 97ms | 5ms | -92ms | -94.85
| UserAccessTokenStore.GetByToken | p99 | 86ms | 5ms | -81ms | -94.18
| StatusStore.GetByIds | p99 | 30ms | 5ms | -25ms | -82.68
| JobStore.Get | p99 | 77ms | 13ms | -64ms | -82.58
| DraftStore.GetDraftsForUser | p99 | 126ms | 23ms | -103ms | -81.60
| PostStore.GetSingle | p99 | 46ms | 9ms | -37ms | -80.91
| DraftStore.Get | p99 | 34ms | 7ms | -27ms | -80.15
| ChannelStore.GetMemberForPost | p99 | 50ms | 10ms | -40ms | -79.86
| LinkMetadataStore.Get | p99 | 48ms | 10ms | -38ms | -79.78
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 10ms | -36ms | -78.69
| ChannelStore.GetSidebarCategory | p99 | 47ms | 10ms | -37ms | -77.90
| ChannelStore.GetChannelUnread | p99 | 21ms | 5ms | -16ms | -75.82
| TeamStore.Get | p99 | 72ms | 18ms | -54ms | -74.92
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 184ms | 49ms | -135ms | -73.55
| ChannelStore.GetFileCount | p99 | 88ms | 24ms | -64ms | -72.72
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 65ms | 18ms | -47ms | -71.87
| ChannelStore.GetChannelsByUser | p99 | 245ms | 69ms | -176ms | -71.74
| EmojiStore.GetByName | p99 | 74ms | 21ms | -53ms | -71.45
| PostStore.GetPosts | p99 | 171ms | 49ms | -122ms | -71.34
| UserStore.GetProfilesByUsernames | p99 | 60ms | 17ms | -43ms | -71.32
| PostPriorityStore.GetForPosts | p99 | 85ms | 25ms | -60ms | -70.99
| PostAcknowledgementStore.GetForPosts | p99 | 81ms | 24ms | -57ms | -70.47
| ChannelStore.GetMemberLastViewedAt | p99 | 178ms | 53ms | -125ms | -70.31
| ThreadStore.GetThreadsForUser | p99 | 83ms | 25ms | -58ms | -70.27
| TeamStore.GetTeamsByUserId | p99 | 188ms | 56ms | -132ms | -70.13
| ThreadStore.GetThreadForUser | p99 | 69ms | 21ms | -48ms | -69.98
| PostStore.GetPostsByThread | p99 | 20ms | 6ms | -14ms | -69.07
| ThreadStore.GetThreadUnreadReplyCount | p99 | 20ms | 6ms | -14ms | -69.06
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 23ms | 7ms | -16ms | -68.82
| PostStore.GetPostsBefore | p99 | 79ms | 25ms | -54ms | -68.61
| PreferenceStore.Get | p99 | 66ms | 21ms | -45ms | -68.28
| TeamStore.GetTeamsForUser | p99 | 174ms | 56ms | -118ms | -67.85
| FileInfoStore.GetByIds | p99 | 90ms | 29ms | -61ms | -67.78
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 177ms | 57ms | -120ms | -67.76
| StatusStore.Get | p99 | 143ms | 47ms | -96ms | -66.99
| ChannelStore.Get | p99 | 201ms | 68ms | -133ms | -66.08
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 144ms | 50ms | -94ms | -65.44
| ThreadStore.GetTeamsUnreadForUser | p99 | 173ms | 60ms | -113ms | -65.22
| ThreadStore.GetTotalThreads | p99 | 140ms | 49ms | -91ms | -65.05
| PostStore.GetEtag | p99 | 169ms | 60ms | -109ms | -64.37
| ChannelStore.GetMembersForUser | p99 | 106ms | 38ms | -68ms | -64.29
| TeamStore.GetAllPage | p99 | 186ms | 67ms | -119ms | -63.90
| ThreadStore.GetTotalUnreadThreads | p99 | 135ms | 49ms | -86ms | -63.48
| UserTermsOfServiceStore.GetByUser | p99 | 197ms | 72ms | -125ms | -63.32
| JobStore.GetAllByTypePage | p99 | 13ms | 5ms | -8ms | -62.95
| ChannelStore.GetChannels | p99 | 118ms | 44ms | -74ms | -62.83
| GroupStore.GetByName | p99 | 209ms | 78ms | -131ms | -62.58
| WebhookStore.GetOutgoingByTeam | p99 | 67ms | 26ms | -41ms | -60.91
| ChannelStore.GetGuestCount | p99 | 216ms | 86ms | -130ms | -60.09
| UserStore.GetAllProfiles | p99 | 117ms | 47ms | -70ms | -59.63
| SessionStore.GetLRUSessions | p99 | 187ms | 77ms | -110ms | -58.75
| UserStore.GetForLogin | p99 | 203ms | 84ms | -119ms | -58.69
| GroupStore.GetGroups | p99 | 92ms | 38ms | -54ms | -58.68
| PreferenceStore.GetAll | p99 | 216ms | 90ms | -126ms | -58.46
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 433ms | 183ms | -250ms | -57.74
| UserStore.IsEmpty | p99 | 99ms | 42ms | -57ms | -57.65
| SessionStore.Get | p99 | 191ms | 83ms | -108ms | -56.52
| SessionStore.Save | p99 | 175ms | 77ms | -98ms | -55.96
| PostStore.SetPostReminder | p99 | 23ms | 10ms | -13ms | -55.68
| ChannelStore.CreateInitialSidebarCategories | p99 | 212ms | 94ms | -118ms | -55.60
| ReactionStore.GetForPost | p99 | 22ms | 10ms | -12ms | -55.17
| ThreadStore.GetTotalUnreadMentions | p99 | 138ms | 63ms | -75ms | -54.16
| UserStore.GetProfileByIds | p99 | 19ms | 9ms | -10ms | -53.72
| ChannelStore.GetByName | p99 | 163ms | 76ms | -87ms | -53.28
| FileInfoStore.Get | p99 | 11ms | 5ms | -6ms | -52.19
| ChannelStore.SaveMember | p99 | 499ms | 242ms | -257ms | -51.54
| ThreadStore.GetThreadFollowers | p99 | 49ms | 24ms | -25ms | -50.61
| PostStore.Get | p99 | 60ms | 30ms | -30ms | -50.35
| BotStore.Save | p99 | 10ms | 5ms | -5ms | -50.25
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 25ms | -25ms | -50.25
| PluginStore.List | p99 | 82ms | 41ms | -41ms | -50.00
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -46.52
| UserStore.Count | p99 | 453ms | 248ms | -205ms | -45.30
| PostStore.SearchPostsForUser | p99 | 448ms | 249ms | -199ms | -44.39
| FileInfoStore.GetForPost | p99 | 9ms | 5ms | -4ms | -44.26
| ThreadStore.GetMembershipForUser | p99 | 41ms | 23ms | -18ms | -44.12
| SystemStore.GetByName | p99 | 16ms | 9ms | -7ms | -43.70
| PostPersistentNotificationStore.GetSingle | p99 | 56ms | 33ms | -23ms | -41.03
| ChannelStore.GetMemberCount | p99 | 832ms | 494ms | -338ms | -40.65
| ChannelStore.GetPublicChannelsForTeam | p99 | 260ms | 158ms | -102ms | -39.22
| PostStore.GetPostIdAfterTime | p99 | 15ms | 9ms | -6ms | -39.01
| ChannelStore.GetMember | p99 | 24ms | 15ms | -9ms | -38.14
| JobStore.GetAllByStatus | p99 | 78ms | 49ms | -29ms | -37.13
| PostStore.Update | p99 | 38ms | 25ms | -13ms | -34.10
| ProductNoticesStore.View | p99 | 142ms | 94ms | -48ms | -33.83
| ChannelStore.UpdateLastViewedAt | p99 | 15ms | 10ms | -5ms | -33.73
| PluginStore.Delete | p99 | 14ms | 10ms | -4ms | -28.92
| PostStore.GetPostsSince | p99 | 94ms | 67ms | -27ms | -28.68
| ChannelStore.GetPinnedPostCount | p99 | 47ms | 34ms | -13ms | -27.84
| ChannelStore.IncrementMentionCount | p99 | 12ms | 9ms | -3ms | -25.24
| UserStore.AutocompleteUsersInChannel | p99 | 706ms | 538ms | -168ms | -23.80
| ChannelStore.GetAllChannelMembersForUser | p99 | 57ms | 45ms | -12ms | -21.03
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 20ms | 16ms | -4ms | -20.26
| UserStore.Save | p99 | 153ms | 123ms | -30ms | -19.66
| UserStore.UpdateFailedPasswordAttempts | p99 | 23ms | 19ms | -4ms | -17.49
| PluginStore.SetWithOptions | p99 | 24ms | 20ms | -4ms | -16.50
| PreferenceStore.Save | p99 | 46ms | 39ms | -7ms | -15.12
| UserStore.UpdateUpdateAt | p99 | 21ms | 18ms | -3ms | -14.48
| UserStore.UpdateLastLogin | p99 | 21ms | 18ms | -3ms | -14.36
| AuditStore.Save | p99 | 22ms | 19ms | -3ms | -13.55
| PostAcknowledgementStore.GetForPost | p99 | 46ms | 40ms | -6ms | -12.97
| ThreadStore.MaintainMembership | p99 | 16ms | 14ms | -2ms | -12.85
| UserStore.Search | p99 | 382ms | 338ms | -44ms | -11.51
| UserStore.GetAllProfilesInChannel | p99 | 2.211s | 2.019s | -192ms | -8.68
| PostStore.Save | p99 | 45ms | 43ms | -2ms | -4.43
| UserStore.GetUnreadCount | p99 | 110ms | 107ms | -3ms | -2.73
| TeamStore.SaveMember | p99 | 250ms | 246ms | -4ms | -1.60
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 29ms | 58ms | 29ms | 99.51
| updateCategoriesForTeamForUser | avg | 55ms | 58ms | 3ms | 5.44
| autocompleteChannelsForTeamForSearch | avg | 126ms | 132ms | 6ms | 4.75
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | p99 | 50ms | 246ms | 196ms | 393.97
| searchGroupChannels | p99 | 39ms | 53ms | 14ms | 35.83
| autocompleteChannelsForTeamForSearch | p99 | 674ms | 736ms | 62ms | 9.19
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 5ms | 0s | -5ms | -107.08
| getUsersByGroupChannelIds | avg | 4ms | 0s | -4ms | -101.11
| createChannel | avg | 224ms | 0s | -224ms | -99.99
| createJob | avg | 3ms | 0s | -3ms | -87.94
| patchPost | avg | 374ms | 61ms | -313ms | -83.64
| getChannelsForUser | avg | 30ms | 7ms | -23ms | -77.43
| getChannel | avg | 16ms | 5ms | -11ms | -69.79
| getChannelMember | avg | 23ms | 8ms | -15ms | -65.94
| getTeamsForUser | avg | 10ms | 4ms | -6ms | -61.28
| getUser | avg | 12ms | 5ms | -7ms | -60.54
| getPreferences | avg | 13ms | 6ms | -7ms | -52.71
| getTeamMembersForUser | avg | 10ms | 5ms | -5ms | -51.04
| getChannelsForTeamForUser | avg | 8ms | 4ms | -4ms | -50.01
| getAllTeams | avg | 10ms | 5ms | -5ms | -49.93
| getCategoriesForTeamForUser | avg | 28ms | 14ms | -14ms | -49.37
| getTeamsUnreadForUser | avg | 14ms | 7ms | -7ms | -48.50
| getDrafts | avg | 6ms | 3ms | -3ms | -46.74
| getChannelMembersForTeamForUser | avg | 7ms | 4ms | -3ms | -44.71
| getPostsForChannelAroundLastUnread | avg | 51ms | 29ms | -22ms | -42.80
| createCategoryForTeamForUser | avg | 35ms | 20ms | -15ms | -42.48
| getThreadsForUser | avg | 6ms | 4ms | -2ms | -33.93
| createDirectChannel | avg | 252ms | 176ms | -76ms | -30.12
| saveReaction | avg | 14ms | 10ms | -4ms | -29.48
| getClientConfig | avg | 8ms | 6ms | -2ms | -24.89
| getPostsForChannel | avg | 32ms | 24ms | -8ms | -24.84
| removeUserCustomStatus | avg | 145ms | 110ms | -35ms | -24.11
| getUsers | avg | 8ms | 6ms | -2ms | -24.02
| login | avg | 89ms | 68ms | -21ms | -23.55
| createGroupChannel | avg | 357ms | 273ms | -84ms | -23.54
| addChannelMember | avg | 239ms | 188ms | -51ms | -21.38
| getChannelStats | avg | 19ms | 15ms | -4ms | -21.18
| createUser | avg | 137ms | 110ms | -27ms | -19.64
| getPublicChannelsForTeam | avg | 17ms | 14ms | -3ms | -17.51
| searchPostsInTeam | avg | 68ms | 57ms | -11ms | -16.10
| updateReadStateThreadByUser | avg | 32ms | 27ms | -5ms | -15.63
| getProfileImage | avg | 90ms | 77ms | -13ms | -14.40
| viewChannel | avg | 14ms | 12ms | -2ms | -14.18
| getPostThread | avg | 14ms | 12ms | -2ms | -13.87
| addTeamMember | avg | 1.383s | 1.235s | -148ms | -10.70
| autocompleteUsers | avg | 175ms | 172ms | -3ms | -1.71
| getAnalytics | avg | 322ms | 317ms | -5ms | -1.55
| createPost | avg | 397ms | 392ms | -5ms | -1.26
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 10ms | 0s | -10ms | -101.01
| createJob | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -100.92
| createChannel | p99 | 249ms | 0s | -249ms | -100.16
| getChannel | p99 | 285ms | 10ms | -275ms | -96.51
| patchPost | p99 | 10s | 500ms | -9.5s | -95.00
| getDrafts | p99 | 127ms | 23ms | -104ms | -82.06
| getChannelUnread | p99 | 21ms | 5ms | -16ms | -75.82
| updateReadStateThreadByUser | p99 | 205ms | 50ms | -155ms | -75.60
| getChannelMember | p99 | 363ms | 92ms | -271ms | -74.70
| getUsersByNames | p99 | 61ms | 17ms | -44ms | -72.56
| getChannelsForTeamForUser | p99 | 173ms | 49ms | -124ms | -71.52
| getTeamsForUser | p99 | 188ms | 56ms | -132ms | -70.10
| deleteDraft | p99 | 34ms | 10ms | -24ms | -69.65
| viewChannel | p99 | 166ms | 51ms | -115ms | -69.43
| getChannelMembersForTeamForUser | p99 | 127ms | 40ms | -87ms | -68.43
| getPostsForChannelAroundLastUnread | p99 | 762ms | 249ms | -513ms | -67.34
| getTeamMember | p99 | 15ms | 5ms | -10ms | -65.07
| getTeamsUnreadForUser | p99 | 237ms | 84ms | -153ms | -64.59
| getTeamMembersForUser | p99 | 192ms | 68ms | -124ms | -64.46
| saveReaction | p99 | 212ms | 79ms | -133ms | -62.66
| getJobsByType | p99 | 13ms | 5ms | -8ms | -62.22
| getAllTeams | p99 | 195ms | 74ms | -121ms | -62.03
| getThreadsForUser | p99 | 99ms | 39ms | -60ms | -60.69
| getUser | p99 | 207ms | 82ms | -125ms | -60.39
| addChannelMember | p99 | 1.061s | 421ms | -640ms | -60.35
| getCategoriesForTeamForUser | p99 | 435ms | 184ms | -251ms | -57.75
| updateCategoriesForTeamForUser | p99 | 233ms | 99ms | -134ms | -57.39
| getPreferences | p99 | 217ms | 93ms | -124ms | -57.12
| getUsers | p99 | 99ms | 46ms | -53ms | -53.52
| getClientConfig | p99 | 81ms | 38ms | -43ms | -53.08
| createDirectChannel | p99 | 785ms | 390ms | -395ms | -50.32
| createCategoryForTeamForUser | p99 | 50ms | 25ms | -25ms | -50.24
| login | p99 | 679ms | 350ms | -329ms | -48.48
| setPostReminder | p99 | 47ms | 25ms | -22ms | -46.56
| logout | p99 | 92ms | 50ms | -42ms | -45.55
| getPostsForChannel | p99 | 391ms | 217ms | -174ms | -44.47
| getChannelsForUser | p99 | 247ms | 142ms | -105ms | -42.54
| getPublicChannelsForTeam | p99 | 260ms | 158ms | -102ms | -39.22
| getPostThread | p99 | 50ms | 31ms | -19ms | -37.63
| removeUserCustomStatus | p99 | 380ms | 248ms | -132ms | -34.74
| upsertDraft | p99 | 23ms | 16ms | -7ms | -30.51
| getProfileImage | p99 | 496ms | 350ms | -146ms | -29.43
| createUser | p99 | 497ms | 362ms | -135ms | -27.18
| getChannelStats | p99 | 441ms | 349ms | -92ms | -20.85
| searchPostsInTeam | p99 | 486ms | 388ms | -98ms | -20.16
| autocompleteUsers | p99 | 602ms | 493ms | -109ms | -18.11
| updatePreferences | p99 | 22ms | 19ms | -3ms | -13.73
| searchUsers | p99 | 394ms | 357ms | -37ms | -9.40
| addTeamMember | p99 | 4.761s | 4.359s | -402ms | -8.44
| getFileThumbnail | p99 | 97ms | 92ms | -5ms | -5.14
| createPost | p99 | 2.324s | 2.219s | -105ms | -4.52
| createGroupChannel | p99 | 1.66s | 1.6s | -60ms | -3.61
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.554
| BotStore.Get |  Avg| 4ms| 6ms | 2ms | 47.999
| |  P99| 46ms| 92ms | 46ms | 100.546
| BotStore.Save |  Avg| 8ms| 4ms | -4ms | -52.803
| |  P99| 10ms| 5ms | -5ms | -50.251
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 279ms| 271ms | -8ms | -2.867
| |  P99| 498ms| 497ms | -1ms | -0.201
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 3ms | -1ms | -26.351
| |  P99| 20ms| 16ms | -4ms | -20.255
| ChannelStore.AnalyticsTypeCount |  Avg| 5ms| 6ms | 1ms | 19.322
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 1.523s| 1.538s | 15ms | 0.985
| |  P99| 4.947s| 4.933s | -14ms | -0.283
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 126ms| 132ms | 6ms | 4.748
| |  P99| 674ms| 736ms | 62ms | 9.194
| ChannelStore.CreateDirectChannel |  Avg| 31ms| 20ms | -11ms | -35.605
| |  P99| 510ms| 26ms | -484ms | -94.920
| ChannelStore.CreateInitialSidebarCategories |  Avg| 26ms| 21ms | -5ms | -19.102
| |  P99| 212ms| 94ms | -118ms | -55.601
| ChannelStore.CreateSidebarCategory |  Avg| 27ms| 18ms | -9ms | -33.413
| |  P99| 50ms| 25ms | -25ms | -50.251
| ChannelStore.Get |  Avg| 9ms| 4ms | -5ms | -55.572
| |  P99| 201ms| 68ms | -133ms | -66.078
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 56ms| 87ms | 31ms | 55.605
| ChannelStore.GetAllChannelMembersForUser |  Avg| 9ms| 8ms | -1ms | -10.879
| |  P99| 57ms| 45ms | -12ms | -21.032
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 19ms| 17ms | -2ms | -10.783
| |  P99| 142ms| 165ms | 23ms | 16.199
| ChannelStore.GetByName |  Avg| 9ms| 6ms | -3ms | -34.391
| |  P99| 163ms| 76ms | -87ms | -53.276
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -34.645
| |  P99| 21ms| 5ms | -16ms | -75.824
| ChannelStore.GetChannels |  Avg| 6ms| 4ms | -2ms | -32.975
| |  P99| 118ms| 44ms | -74ms | -62.826
| ChannelStore.GetChannelsByUser |  Avg| 28ms| 6ms | -22ms | -79.327
| |  P99| 245ms| 69ms | -176ms | -71.735
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 4ms| 3ms | -1ms | -25.627
| |  P99| 65ms| 18ms | -47ms | -71.866
| ChannelStore.GetFileCount |  Avg| 6ms| 5ms | -1ms | -15.968
| |  P99| 88ms| 24ms | -64ms | -72.721
| ChannelStore.GetGuestCount |  Avg| 11ms| 5ms | -6ms | -52.426
| |  P99| 216ms| 86ms | -130ms | -60.092
| ChannelStore.GetMember |  Avg| 3ms| 2ms | -1ms | -36.361
| |  P99| 24ms| 15ms | -9ms | -38.135
| ChannelStore.GetMemberCount |  Avg| 172ms| 141ms | -31ms | -18.030
| |  P99| 832ms| 494ms | -338ms | -40.646
| ChannelStore.GetMemberForPost |  Avg| 4ms| 3ms | -1ms | -26.443
| |  P99| 50ms| 10ms | -40ms | -79.864
| ChannelStore.GetMemberLastViewedAt |  Avg| 8ms| 4ms | -4ms | -49.000
| |  P99| 178ms| 53ms | -125ms | -70.310
| ChannelStore.GetMembers |  Avg| 4ms| 0s | -4ms | -106.940
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 6ms| 4ms | -2ms | -33.151
| |  P99| 106ms| 38ms | -68ms | -64.287
| ChannelStore.GetMembersForUserWithPagination |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 47ms| 34ms | -13ms | -27.839
| ChannelStore.GetPublicChannelsForTeam |  Avg| 16ms| 13ms | -3ms | -18.785
| |  P99| 260ms| 158ms | -102ms | -39.221
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 28ms| 14ms | -14ms | -49.803
| |  P99| 433ms| 183ms | -250ms | -57.735
| ChannelStore.GetSidebarCategory |  Avg| 9ms| 6ms | -3ms | -33.450
| |  P99| 47ms| 10ms | -37ms | -77.896
| ChannelStore.GetTeamChannels |  Avg| 45ms| 0s | -45ms | -99.962
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -25.240
| ChannelStore.Save |  Avg| 12ms| 11ms | -1ms | -8.192
| |  P99| 71ms| 70ms | -1ms | -1.408
| ChannelStore.SaveMember |  Avg| 54ms| 38ms | -16ms | -29.562
| |  P99| 499ms| 242ms | -257ms | -51.537
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 53ms | 14ms | 35.834
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -33.734
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 59ms | 27ms | 83.103
| |  P99| 95ms| 238ms | 143ms | 151.321
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.056
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 6ms | 3ms | 110.137
| |  P99| 7ms| 47ms | 40ms | 553.633
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 12ms | -1ms | -7.482
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.Get |  Avg| 3ms| 2ms | -1ms | -31.494
| |  P99| 34ms| 7ms | -27ms | -80.148
| DraftStore.GetDraftsForUser |  Avg| 6ms| 3ms | -3ms | -47.949
| |  P99| 126ms| 23ms | -103ms | -81.596
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 4ms| 2ms | -2ms | -52.805
| |  P99| 74ms| 21ms | -53ms | -71.445
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 3ms| 2ms | -1ms | -37.386
| |  P99| 11ms| 5ms | -6ms | -52.190
| FileInfoStore.GetByIds |  Avg| 6ms| 4ms | -2ms | -31.398
| |  P99| 90ms| 29ms | -61ms | -67.783
| FileInfoStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -35.585
| |  P99| 9ms| 5ms | -4ms | -44.256
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.741
| FileInfoStore.SetContent |  Avg| 7ms| 8ms | 1ms | 13.363
| |  P99| 22ms| 23ms | 1ms | 4.594
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 8ms| 4ms | -4ms | -48.772
| |  P99| 184ms| 49ms | -135ms | -73.550
| GroupStore.GetByName |  Avg| 10ms| 5ms | -5ms | -52.268
| |  P99| 209ms| 78ms | -131ms | -62.575
| GroupStore.GetGroups |  Avg| 5ms| 3ms | -2ms | -37.258
| |  P99| 92ms| 38ms | -54ms | -58.682
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 4ms| 2ms | -2ms | -45.875
| |  P99| 77ms| 13ms | -64ms | -82.581
| JobStore.GetAllByStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 78ms| 49ms | -29ms | -37.131
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -62.951
| JobStore.GetCountByStatusAndType |  Avg| 9ms| 2ms | -7ms | -74.659
| |  P99| 209ms| 5ms | -204ms | -97.725
| JobStore.GetNewestJobByStatusesAndType |  Avg| 10ms| 3ms | -7ms | -73.481
| |  P99| 220ms| 5ms | -215ms | -97.727
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.391
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 30.714
| |  P99| 8ms| 35ms | 27ms | 318.303
| JobStore.UpdateStatus |  Avg| 4ms| 5ms | 1ms | 28.498
| |  P99| 9ms| 77ms | 68ms | 719.280
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 97.048
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 3ms| 2ms | -1ms | -29.782
| |  P99| 48ms| 10ms | -38ms | -79.777
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 2ms | -1ms | -38.897
| |  P99| 14ms| 10ms | -4ms | -28.923
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 5ms| 3ms | -2ms | -41.881
| |  P99| 82ms| 41ms | -41ms | -50.000
| PluginStore.SetWithOptions |  Avg| 6ms| 5ms | -1ms | -16.815
| |  P99| 24ms| 20ms | -4ms | -16.500
| PostAcknowledgementStore.GetForPost |  Avg| 5ms| 4ms | -1ms | -21.191
| |  P99| 46ms| 40ms | -6ms | -12.972
| PostAcknowledgementStore.GetForPosts |  Avg| 5ms| 4ms | -1ms | -19.031
| |  P99| 81ms| 24ms | -57ms | -70.466
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 3ms | 1ms | 60.947
| |  P99| 5ms| 43ms | 38ms | 767.677
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 4ms| 3ms | -1ms | -28.260
| |  P99| 56ms| 33ms | -23ms | -41.030
| PostPriorityStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 30.153
| |  P99| 46ms| 45ms | -1ms | -2.162
| PostPriorityStore.GetForPosts |  Avg| 5ms| 3ms | -2ms | -37.607
| |  P99| 85ms| 25ms | -60ms | -70.989
| PostStore.AnalyticsPostCount |  Avg| 2ms| 633ms | 631ms | 26913.354
| |  P99| 5ms| 2.47s | 2.465s | 49762.439
| PostStore.Delete |  Avg| 14ms| 13ms | -1ms | -7.280
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 7ms| 6ms | -1ms | -15.264
| |  P99| 60ms| 30ms | -30ms | -50.351
| PostStore.GetEtag |  Avg| 7ms| 4ms | -3ms | -40.793
| |  P99| 169ms| 60ms | -109ms | -64.367
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 9ms | -6ms | -39.012
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.524
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 6ms | -1ms | -15.222
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 11ms| 7ms | -4ms | -35.993
| |  P99| 171ms| 49ms | -122ms | -71.339
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.522
| PostStore.GetPostsBefore |  Avg| 6ms| 4ms | -2ms | -35.218
| |  P99| 79ms| 25ms | -54ms | -68.613
| PostStore.GetPostsByThread |  Avg| 3ms| 2ms | -1ms | -34.626
| |  P99| 20ms| 6ms | -14ms | -69.069
| PostStore.GetPostsSince |  Avg| 11ms| 9ms | -2ms | -18.652
| |  P99| 94ms| 67ms | -27ms | -28.683
| PostStore.GetSingle |  Avg| 4ms| 3ms | -1ms | -28.268
| |  P99| 46ms| 9ms | -37ms | -80.909
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.431
| PostStore.SearchPostsForUser |  Avg| 59ms| 50ms | -9ms | -15.318
| |  P99| 448ms| 249ms | -199ms | -44.386
| PostStore.SetPostReminder |  Avg| 7ms| 6ms | -1ms | -14.570
| |  P99| 23ms| 10ms | -13ms | -55.677
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 38ms| 25ms | -13ms | -34.102
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 4ms| 3ms | -1ms | -25.541
| |  P99| 66ms| 21ms | -45ms | -68.281
| PreferenceStore.GetAll |  Avg| 13ms| 6ms | -7ms | -53.779
| |  P99| 216ms| 90ms | -126ms | -58.459
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 46ms| 39ms | -7ms | -15.123
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 29ms| 28ms | -1ms | -3.390
| |  P99| 142ms| 94ms | -48ms | -33.829
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -55.167
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -127.855
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -108.030
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 11ms| 7ms | -4ms | -35.155
| |  P99| 191ms| 83ms | -108ms | -56.519
| SessionStore.GetLRUSessions |  Avg| 9ms| 5ms | -4ms | -44.779
| |  P99| 187ms| 77ms | -110ms | -58.752
| SessionStore.GetSessionsExpired |  Avg| 13ms| 2ms | -11ms | -85.520
| |  P99| 97ms| 5ms | -92ms | -94.845
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -33.965
| |  P99| 23ms| 7ms | -16ms | -68.824
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 13ms| 9ms | -4ms | -30.874
| |  P99| 175ms| 77ms | -98ms | -55.959
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.717
| StatusStore.Get |  Avg| 7ms| 4ms | -3ms | -43.557
| |  P99| 143ms| 47ms | -96ms | -66.988
| StatusStore.GetByIds |  Avg| 3ms| 2ms | -1ms | -35.197
| |  P99| 30ms| 5ms | -25ms | -82.680
| StatusStore.SaveOrUpdate |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.860
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 6ms | -2ms | -26.007
| |  P99| 46ms| 10ms | -36ms | -78.689
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.064
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -43.703
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 4ms| 3ms | -1ms | -25.489
| |  P99| 72ms| 18ms | -54ms | -74.919
| TeamStore.GetAllPage |  Avg| 9ms| 4ms | -5ms | -55.411
| |  P99| 186ms| 67ms | -119ms | -63.897
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 4ms | -5ms | -57.387
| |  P99| 177ms| 57ms | -120ms | -67.763
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 10ms| 4ms | -6ms | -61.756
| |  P99| 188ms| 56ms | -132ms | -70.130
| TeamStore.GetTeamsForUser |  Avg| 8ms| 4ms | -4ms | -48.334
| |  P99| 174ms| 56ms | -118ms | -67.855
| TeamStore.SaveMember |  Avg| 103ms| 98ms | -5ms | -4.837
| |  P99| 250ms| 246ms | -4ms | -1.601
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 23ms | -18ms | -44.117
| ThreadStore.GetTeamsUnreadForUser |  Avg| 9ms| 5ms | -4ms | -44.796
| |  P99| 173ms| 60ms | -113ms | -65.221
| ThreadStore.GetThreadFollowers |  Avg| 4ms| 3ms | -1ms | -26.706
| |  P99| 49ms| 24ms | -25ms | -50.613
| ThreadStore.GetThreadForUser |  Avg| 6ms| 5ms | -1ms | -16.113
| |  P99| 69ms| 21ms | -48ms | -69.977
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 2ms | -1ms | -30.631
| |  P99| 20ms| 6ms | -14ms | -69.064
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 3ms | -2ms | -41.535
| |  P99| 83ms| 25ms | -58ms | -70.266
| ThreadStore.GetTotalThreads |  Avg| 7ms| 4ms | -3ms | -42.439
| |  P99| 140ms| 49ms | -91ms | -65.049
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 4ms | -3ms | -44.043
| |  P99| 138ms| 63ms | -75ms | -54.157
| ThreadStore.GetTotalUnreadThreads |  Avg| 7ms| 4ms | -3ms | -42.871
| |  P99| 135ms| 49ms | -86ms | -63.477
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 7ms| 4ms | -3ms | -41.658
| |  P99| 144ms| 50ms | -94ms | -65.442
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.849
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 4ms| 2ms | -2ms | -45.545
| |  P99| 86ms| 5ms | -81ms | -94.183
| UserStore.AnalyticsActiveCount |  Avg| 212ms| 210ms | -2ms | -0.945
| |  P99| 249ms| 248ms | -1ms | -0.402
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 202ms| 201ms | -1ms | -0.494
| |  P99| 706ms| 538ms | -168ms | -23.796
| UserStore.Count |  Avg| 93ms| 82ms | -11ms | -11.777
| |  P99| 453ms| 248ms | -205ms | -45.304
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.014
| UserStore.GetAllProfiles |  Avg| 8ms| 5ms | -3ms | -35.746
| |  P99| 117ms| 47ms | -70ms | -59.634
| UserStore.GetAllProfilesInChannel |  Avg| 475ms| 448ms | -27ms | -5.682
| |  P99| 2.211s| 2.019s | -192ms | -8.685
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 53ms| 52ms | -1ms | -1.869
| UserStore.GetForLogin |  Avg| 10ms| 5ms | -5ms | -49.899
| |  P99| 203ms| 84ms | -119ms | -58.690
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -100.664
| |  P99| 5ms| 0s | -5ms | -100.919
| UserStore.GetProfileByIds |  Avg| 3ms| 2ms | -1ms | -37.993
| |  P99| 19ms| 9ms | -10ms | -53.722
| UserStore.GetProfilesByUsernames |  Avg| 4ms| 3ms | -1ms | -24.478
| |  P99| 60ms| 17ms | -43ms | -71.321
| UserStore.GetProfilesNotInChannel |  Avg| 6ms| 0s | -6ms | -105.497
| |  P99| 10ms| 0s | -10ms | -100.503
| UserStore.GetUnreadCount |  Avg| 7ms| 8ms | 1ms | 15.051
| |  P99| 110ms| 107ms | -3ms | -2.734
| UserStore.IsEmpty |  Avg| 5ms| 3ms | -2ms | -37.352
| |  P99| 99ms| 42ms | -57ms | -57.647
| UserStore.Save |  Avg| 69ms| 68ms | -1ms | -1.455
| |  P99| 153ms| 123ms | -30ms | -19.660
| UserStore.Search |  Avg| 94ms| 93ms | -1ms | -1.066
| |  P99| 382ms| 338ms | -44ms | -11.509
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.489
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.362
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.485
| UserTermsOfServiceStore.GetByUser |  Avg| 10ms| 4ms | -6ms | -62.838
| |  P99| 197ms| 72ms | -125ms | -63.318
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 4ms | -1ms | -18.762
| |  P99| 67ms| 26ms | -41ms | -60.912
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 239ms| 188ms | -51ms | -21.375
| | P99| 1.061s| 421ms | -640ms | -60.347
| addTeamMember | Avg| 1.383s| 1.235s | -148ms | -10.700
| | P99| 4.761s| 4.359s | -402ms | -8.443
| autocompleteChannelsForTeamForSearch | Avg| 126ms| 132ms | 6ms | 4.746
| | P99| 674ms| 736ms | 62ms | 9.194
| autocompleteEmojis | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 175ms| 172ms | -3ms | -1.712
| | P99| 602ms| 493ms | -109ms | -18.113
| createCategoryForTeamForUser | Avg| 35ms| 20ms | -15ms | -42.475
| | P99| 50ms| 25ms | -25ms | -50.236
| createChannel | Avg| 224ms| 0s | -224ms | -99.986
| | P99| 249ms| 0s | -249ms | -100.162
| createDirectChannel | Avg| 252ms| 176ms | -76ms | -30.125
| | P99| 785ms| 390ms | -395ms | -50.322
| createGroupChannel | Avg| 357ms| 273ms | -84ms | -23.541
| | P99| 1.66s| 1.6s | -60ms | -3.614
| createJob | Avg| 3ms| 0s | -3ms | -87.942
| | P99| 5ms| 0s | -5ms | -101.010
| createPost | Avg| 397ms| 392ms | -5ms | -1.258
| | P99| 2.324s| 2.219s | -105ms | -4.518
| createUser | Avg| 137ms| 110ms | -27ms | -19.640
| | P99| 497ms| 362ms | -135ms | -27.179
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 10ms | -24ms | -69.652
| deletePost | Avg| 21ms| 20ms | -1ms | -4.807
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 11ms | 1ms | 9.577
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 10ms| 5ms | -5ms | -49.932
| | P99| 195ms| 74ms | -121ms | -62.029
| getAnalytics | Avg| 322ms| 317ms | -5ms | -1.554
| | P99| 498ms| 498ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 28ms| 14ms | -14ms | -49.375
| | P99| 435ms| 184ms | -251ms | -57.752
| getChannel | Avg| 16ms| 5ms | -11ms | -69.794
| | P99| 285ms| 10ms | -275ms | -96.514
| getChannelMember | Avg| 23ms| 8ms | -15ms | -65.939
| | P99| 363ms| 92ms | -271ms | -74.699
| getChannelMembers | Avg| 5ms| 0s | -5ms | -107.077
| | P99| 10ms| 0s | -10ms | -101.010
| getChannelMembersForTeamForUser | Avg| 7ms| 4ms | -3ms | -44.706
| | P99| 127ms| 40ms | -87ms | -68.434
| getChannelMembersForUser | Avg| 16ms| 15ms | -1ms | -6.244
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 19ms| 15ms | -4ms | -21.179
| | P99| 441ms| 349ms | -92ms | -20.845
| getChannelUnread | Avg| 4ms| 3ms | -1ms | -23.763
| | P99| 21ms| 5ms | -16ms | -75.824
| getChannelsForTeamForUser | Avg| 8ms| 4ms | -4ms | -50.013
| | P99| 173ms| 49ms | -124ms | -71.523
| getChannelsForUser | Avg| 30ms| 7ms | -23ms | -77.434
| | P99| 247ms| 142ms | -105ms | -42.535
| getClientConfig | Avg| 8ms| 6ms | -2ms | -24.894
| | P99| 81ms| 38ms | -43ms | -53.081
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 6ms| 3ms | -3ms | -46.738
| | P99| 127ms| 23ms | -104ms | -82.063
| getFilePreview | Avg| 45ms| 46ms | 1ms | 2.226
| | P99| 216ms| 217ms | 1ms | 0.463
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 97ms| 92ms | -5ms | -5.140
| getFilteredUsersStats | Avg| 29ms| 58ms | 29ms | 99.511
| | P99| 50ms| 246ms | 196ms | 393.970
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 5ms | -8ms | -62.218
| getPostThread | Avg| 14ms| 12ms | -2ms | -13.872
| | P99| 50ms| 31ms | -19ms | -37.631
| getPostsForChannel | Avg| 32ms| 24ms | -8ms | -24.841
| | P99| 391ms| 217ms | -174ms | -44.468
| getPostsForChannelAroundLastUnread | Avg| 51ms| 29ms | -22ms | -42.804
| | P99| 762ms| 249ms | -513ms | -67.341
| getPreferences | Avg| 13ms| 6ms | -7ms | -52.714
| | P99| 217ms| 93ms | -124ms | -57.119
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 3ms| 2ms | -1ms | -37.892
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 90ms| 77ms | -13ms | -14.404
| | P99| 496ms| 350ms | -146ms | -29.430
| getPublicChannelsForTeam | Avg| 17ms| 14ms | -3ms | -17.507
| | P99| 260ms| 158ms | -102ms | -39.221
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 5ms | -10ms | -65.067
| getTeamMembersForUser | Avg| 10ms| 5ms | -5ms | -51.044
| | P99| 192ms| 68ms | -124ms | -64.457
| getTeamsForUser | Avg| 10ms| 4ms | -6ms | -61.279
| | P99| 188ms| 56ms | -132ms | -70.097
| getTeamsUnreadForUser | Avg| 14ms| 7ms | -7ms | -48.502
| | P99| 237ms| 84ms | -153ms | -64.594
| getThreadsForUser | Avg| 6ms| 4ms | -2ms | -33.927
| | P99| 99ms| 39ms | -60ms | -60.693
| getUser | Avg| 12ms| 5ms | -7ms | -60.544
| | P99| 207ms| 82ms | -125ms | -60.387
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 8ms| 6ms | -2ms | -24.021
| | P99| 99ms| 46ms | -53ms | -53.518
| getUsersByGroupChannelIds | Avg| 4ms| 0s | -4ms | -101.114
| | P99| 5ms| 0s | -5ms | -100.918
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 4ms| 3ms | -1ms | -23.579
| | P99| 61ms| 17ms | -44ms | -72.559
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 89ms| 68ms | -21ms | -23.553
| | P99| 679ms| 350ms | -329ms | -48.479
| logout | Avg| 36ms| 37ms | 1ms | 2.789
| | P99| 92ms| 50ms | -42ms | -45.551
| patchPost | Avg| 374ms| 61ms | -313ms | -83.644
| | P99| 10s| 500ms | -9.5s | -95.000
| removeUserCustomStatus | Avg| 145ms| 110ms | -35ms | -24.110
| | P99| 380ms| 248ms | -132ms | -34.740
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 14ms| 10ms | -4ms | -29.476
| | P99| 212ms| 79ms | -133ms | -62.665
| searchAllChannels | Avg| 1.523s| 1.538s | 15ms | 0.985
| | P99| 4.947s| 4.933s | -14ms | -0.283
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 39ms| 53ms | 14ms | 35.834
| searchPostsInTeam | Avg| 68ms| 57ms | -11ms | -16.104
| | P99| 486ms| 388ms | -98ms | -20.159
| searchUsers | Avg| 96ms| 95ms | -1ms | -1.047
| | P99| 394ms| 357ms | -37ms | -9.398
| setPostReminder | Avg| 18ms| 17ms | -1ms | -5.710
| | P99| 47ms| 25ms | -22ms | -46.556
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 55ms| 58ms | 3ms | 5.441
| | P99| 233ms| 99ms | -134ms | -57.389
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 22ms| 19ms | -3ms | -13.731
| updateReadStateThreadByUser | Avg| 32ms| 27ms | -5ms | -15.629
| | P99| 205ms| 50ms | -155ms | -75.602
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 372ms| 374ms | 2ms | 0.537
| | P99| 994ms| 990ms | -4ms | -0.402
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 16ms | -7ms | -30.511
| viewChannel | Avg| 14ms| 12ms | -2ms | -14.177
| | P99| 166ms| 51ms | -115ms | -69.430
